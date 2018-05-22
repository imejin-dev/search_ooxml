# search_ooxml
Wordのooxml調査用レポジトリ

## ディレクトリ構成
```
.
├── README.md
├── search.docx
├── search.zip
└── unzip
    ├── [Content_Types].xml
    ├── _rels
    ├── docProps
    │   ├── app.xml
    │   ├── core.xml
    │   └── thumbnail.jpeg
    └── word
        ├── _rels
        │   └── document.xml.rels
        ├── document.xml
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
