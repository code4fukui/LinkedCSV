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

ベース・レジストリ データカタログの開催予定イベントをLinkedCSVで提供するもの

```json
{
  "@context": "https://code4fukui.github.io/LinkedCSV/LinkedCSV.jsonld",
  "@type": "LinkedCSV:LinkedCSV",
  "LinkedCSV:contextUrl": "event-schema.jsonld",
  "schema:distribution": {
    "schema:url": "event-latest.csv"
  }
}
```

- https://code4fukui.github.io/event-japan/data-latest/event-latest.csv.jsonld LinkedCSV(JSONLD)
- https://code4fukui.github.io/event-japan/data-latest/event-schema.jsonld schema of CSV(JSONLD)
- https://code4fukui.github.io/event-japan/data-latest/event-latest.csv data(CSV)

