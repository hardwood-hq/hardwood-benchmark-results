| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.5 % |
| Filter | hardwoodDefault[selective] | 5.72 | ±1.9 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 6.87 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.397 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.9 | ±1.1 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 30.0 | ±2.3 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.6 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 65.1 (not settled) | ±0.7 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,332 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 537 (not settled) | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 219 | ±1.0 % |
| BinaryScan | hardwoodRowStrings | 1,001 | ±1.5 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 149 | ±1.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,820 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 177 | ±1.0 % |
| FlatScan | hardwoodColumnar | 291 | ±0.6 % |
| FlatScan | hardwoodRowReaderIndexed | 413 | ±2.5 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 122 | ±0.6 % |
| NarrowScan | hardwoodRowReaderIndexed | 180 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 27,999 | ±2.0 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 14.6 | ±0.2 % |
| FixedSizeListScan | rowFast[768] | 22.5 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 | ±0.5 % |
| Write | hardwoodRow[ZSTD] | 298 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.6 | ±0.6 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 120 | ±0.6 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 207 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 306 | ±1.4 % |
| S3Scan | hardwoodLargeBloomLookup | 112 | ±2.5 % |
| S3Scan | hardwoodMultiFileScan | 530 | ±5.0 % |
| S3Scan | hardwoodProjectedScan | 186 | ±1.6 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 251 | ±0.3 % |
| S3Scan | hardwoodWideFilteredScan | 310 | ±1.2 % |
