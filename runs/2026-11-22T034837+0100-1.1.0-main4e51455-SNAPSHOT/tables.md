| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.5 | ±1.3 % |
| Filter | hardwoodDefault[selective] | 5.91 | ±0.7 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.1 % |
| Filter | hardwoodRowReader[selective] | 7.12 (not settled) | ±0.8 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.377 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.5 | ±2.3 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 30.0 (bimodal) | ±10.4 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.4 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 64.9 (not settled) | ±2.2 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,333 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 543 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 224 | ±0.8 % |
| BinaryScan | hardwoodRowStrings | 994 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 161 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,742 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 290 | ±0.2 % |
| FlatScan | hardwoodRowReaderIndexed | 413 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 121 | ±0.2 % |
| NarrowScan | hardwoodRowReaderIndexed | 180 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.2 % |
| Write | hardwoodRow[ZSTD] | 301 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.5 | ±0.9 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 120 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 205 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main4e51455-SNAPSHOT ms | 1.1.0-main4e51455-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 400 | ±0.6 % |
| S3Scan | hardwoodLargeBloomLookup | 346 | ±0.5 % |
| S3Scan | hardwoodMultiFileScan | 532 | ±8.1 % |
| S3Scan | hardwoodProjectedScan | 185 | ±0.7 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 244 | ±3.8 % |
| S3Scan | hardwoodWideFilteredScan | 313 | ±0.8 % |
