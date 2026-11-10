# Harborline Media Group — Rights & Licensing Ledger

Licensed content decisions are stored as JSON records under `licensing/`. One record per acquisition.

## Selection record schema

```json
{
  "catalog_id": "<stable catalogue identifier>",
  "provider": "<publisher exactly as recorded in the catalogue metadata>",
  "title": "<catalogue title>"
}
```

Records are added by the content licensing desk only. The ledger is authoritative; downstream royalty reporting reads these records.
