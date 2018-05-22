# search_ooxml
Wordのooxml調査用レポジトリ

## ディレクトリ構成
```
.
├── README.md
├── search.docx - Wordファイル
├── search.zip  - Wordファイルの拡張子をzipに変更したもの
└── unzip - search.zipの解凍用ディレクトリ
    ├── [Content_Types].xml
    ├── _rels - リレーションシップ(2つのパーツ感の関係を表す)
    │   └── document.xml.rels
    ├── docProps - プロパティ系XML格納用
    │   ├── app.xml  - ページ数、テキストの行数、アプリケーションのバージョンなど
    │   ├── core.xml - 表題、副題、作成者、作成日時、編集日時
    │   └── thumbnail.jpeg
    └── word
        ├── _rels
        │   └── document.xml.rels
        ├── document.xml  - ドキュメントの本文用のテキスト
        ├── fontTable.xml
        ├── settings.xml
        ├── styles.xml
        ├── stylesWithEffects.xml
        ├── theme
        │   └── theme1.xml
        └── webSettings.xml
```

## Word解凍用コマンド
```
cp search.docx search.zip
unzip -o -d unzip search.zip
```
