| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 25.0 | ±0.7 % |
| Filter | hardwoodDefault[selective] | 5.54 | ±0.5 % |
| Filter | hardwoodRowReader[matchAll] | 38.9 | ±0.3 % |
| Filter | hardwoodRowReader[selective] | 7.05 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.061 (not settled) | ±14.3 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 18.4 | ±0.6 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.4 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 35.9 | ±0.3 % |
| DictionaryFilter | hardwoodRowLtWide | 68.7 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,445 | ±0.3 % |
| OneBrc | hardwoodColumnSplits | 798 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 476 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 960 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 204 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 4,706 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 248 | ±0.7 % |
| FlatScan | hardwoodColumnar | 381 | ±0.5 % |
| FlatScan | hardwoodRowReaderIndexed | 533 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 164 | ±0.3 % |
| NarrowScan | hardwoodRowReaderIndexed | 219 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 2,880 (bimodal) | ±5.8 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 25.2 | ±0.2 % |
| FixedSizeListScan | rowFast[768] | 27.1 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.8 % |
| Write | hardwoodRow[ZSTD] | 300 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 46.9 | ±0.7 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 114 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 119 | ±2.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 207 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main74c76ca-SNAPSHOT ms | 1.1.0-main74c76ca-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 403 | ±0.5 % |
| S3Scan | hardwoodLargeBloomLookup | 336 | ±0.2 % |
| S3Scan | hardwoodMultiFileScan | 1,431 | ±0.8 % |
| S3Scan | hardwoodProjectedScan | 292 | ±0.9 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 394 | ±1.2 % |
| S3Scan | hardwoodWideFilteredScan | 1,076 | ±0.1 % |
