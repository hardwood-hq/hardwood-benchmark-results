| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.4 | ±0.4 % |
| Filter | hardwoodDefault[selective] | 5.06 | ±0.2 % |
| Filter | hardwoodRowReader[matchAll] | 39.5 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 7.68 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.220 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.3 | ±1.1 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 30.6 (bimodal) | ±9.6 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.3 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 66.4 (not settled) | ±1.4 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,340 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 546 (not settled) | ±0.1 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 217 | ±0.3 % |
| BinaryScan | hardwoodRowStrings | 997 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 158 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,512 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 165 | ±0.4 % |
| FlatScan | hardwoodColumnar | 284 | ±0.1 % |
| FlatScan | hardwoodRowReaderIndexed | 434 | ±1.7 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 114 (not settled) | ±0.6 % |
| NarrowScan | hardwoodRowReaderIndexed | 177 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 739 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 15.1 | ±0.2 % |
| FixedSizeListScan | rowFast[768] | 23.9 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±1.1 % |
| Write | hardwoodRow[ZSTD] | 299 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 34.6 | ±0.8 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 101 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 120 | ±0.9 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 207 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main69cb847-SNAPSHOT ms | 1.1.0-main69cb847-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 399 | ±0.2 % |
| S3Scan | hardwoodLargeBloomLookup | 336 | ±0.4 % |
| S3Scan | hardwoodMultiFileScan | 1,450 | ±0.7 % |
| S3Scan | hardwoodProjectedScan | 283 | ±0.8 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 1,076 | ±0.5 % |
| S3Scan | hardwoodWideFilteredScan | 1,077 | ±0.2 % |
