| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±1.6 % |
| Filter | hardwoodDefault[selective] | 5.41 | ±0.6 % |
| Filter | hardwoodRowReader[matchAll] | 38.6 | ±0.3 % |
| Filter | hardwoodRowReader[selective] | 6.68 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.400 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 | ±1.7 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.7 (bimodal) | ±9.7 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.6 % |
| DictionaryFilter | hardwoodRowLtWide | 44.4 | ±2.5 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,309 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 503 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 221 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 1,007 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 167 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,922 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 150 | ±1.4 % |
| FlatScan | hardwoodColumnar | 275 | ±0.6 % |
| FlatScan | hardwoodRowReaderIndexed | 441 | ±2.0 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 94.6 | ±0.8 % |
| NarrowScan | hardwoodRowReaderIndexed | 170 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 40,554 | ±2.8 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.4 | ±0.3 % |
| FixedSizeListScan | rowFast[768] | 19.5 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.5 % |
| Write | hardwoodRow[ZSTD] | 313 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.4 | ±0.2 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.8 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±0.4 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5f3b191-SNAPSHOT ms | 1.1.0-main5f3b191-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 307 | ±0.9 % |
| S3Scan | hardwoodLargeBloomLookup | 113 | ±1.5 % |
| S3Scan | hardwoodMultiFileScan | 490 | ±7.8 % |
| S3Scan | hardwoodProjectedScan | 174 | ±1.3 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 237 | ±7.1 % |
| S3Scan | hardwoodWideFilteredScan | 310 | ±0.9 % |
