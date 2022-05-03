# LinkedCSV

A schema of LinkedCSV extends [schema:Dataset](https://schema.org/Dataset) (This has a property contextUrl as URL for context.jsonld for CSV as a linked data file)

[schema:Dataset](https://schema.org/Dataset) を拡張した LinkedCSV　(context.jsonld へのリンク、contextUrlプロパティを持ち、CSVファイルをLinkedDataにする)

- [LinkedCSV.jsonld](LinkedCSV.jsonld)

## contextUrl

URL for context.jsonld for CSV as a linked data file

context.jsonld へのリンク URL

## web

https://code4fukui.github.io/CSV/

## sample

- [event-latest.csv.jsonld](https://code4fukui.github.io/event-japan/data-latest/event-latest.csv.jsonld)

ベース・レジストリ データカタログのイベントをLinkedCSVに変換したもの

```json
{
  "@context": "https://code4fukui.github.io/LinkedDataset/LinkedDataset.jsonld",
  "@type": "ld:LinkedDataset",
  "ld:contextUrl": "event-schema.jsonld",
  "schema:distribution": {
    "schema:url": "event-latest.csv"
  }
}
```
