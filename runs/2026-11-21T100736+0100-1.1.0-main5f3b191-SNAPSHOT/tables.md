| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.1 | ±1.0 % |
| Filter | hardwoodDefault[selective] | 5.43 (not settled) | ±3.9 % |
| Filter | hardwoodRowReader[matchAll] | 39.2 | ±0.4 % |
| Filter | hardwoodRowReader[selective] | 6.97 (not settled) | ±0.7 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.419 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.8 | ±0.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.0 | ±1.9 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±2.3 % |
| DictionaryFilter | hardwoodRowLtWide | 43.9 (not settled) | ±0.9 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,313 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 495 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 227 | ±1.1 % |
| BinaryScan | hardwoodRowStrings | 1,006 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 156 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodColumnReaders | 2,423 | ±1.2 % |
| NestedScan | hardwoodRowReaderTyped | 156 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 274 | ±0.7 % |
| FlatScan | hardwoodRowReaderIndexed | 446 (bimodal) | ±4.0 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 95.0 | ±0.9 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 (not settled) | ±0.4 % |
| Write | hardwoodRow[ZSTD] | 315 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.1 | ±1.1 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 68.2 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 109 | ±0.9 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodLargeBloomLookup | 570 | ±2.8 % |
| S3Scan | hardwoodMultiFileScan | 584 (not settled) | ±6.2 % |
| S3Scan | hardwoodProjectedScan | 192 (not settled) | ±1.8 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 264 | ±3.5 % |
| S3Scan | hardwoodWideFilteredScan | 338 | ±1.3 % |
