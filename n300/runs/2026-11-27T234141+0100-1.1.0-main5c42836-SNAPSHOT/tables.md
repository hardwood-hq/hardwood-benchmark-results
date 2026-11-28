| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±1.3 % |
| Filter | hardwoodDefault[selective] | 5.18 | ±4.3 % |
| Filter | hardwoodRowReader[matchAll] | 38.6 | ±0.3 % |
| Filter | hardwoodRowReader[selective] | 6.74 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.399 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.6 | ±1.3 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.9 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 9.84 | ±2.0 % |
| DictionaryFilter | hardwoodRowLtWide | 43.4 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,313 | ±0.3 % |
| OneBrc | hardwoodColumnSplits | 503 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 222 | ±0.3 % |
| BinaryScan | hardwoodRowStrings | 996 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 165 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,880 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 146 | ±1.5 % |
| FlatScan | hardwoodColumnar | 277 | ±1.1 % |
| FlatScan | hardwoodRowReaderIndexed | 432 | ±1.9 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 92.7 | ±1.3 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 43,031 | ±5.6 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.5 | ±0.6 % |
| FixedSizeListScan | rowFast[768] | 19.5 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 102 | ±0.3 % |
| Write | hardwoodRow[ZSTD] | 316 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.3 | ±1.8 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.6 | ±0.7 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±2.9 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 306 | ±0.9 % |
| S3Scan | hardwoodLargeBloomLookup | 111 | ±2.7 % |
| S3Scan | hardwoodMultiFileScan | 507 | ±9.5 % |
| S3Scan | hardwoodProjectedScan | 175 | ±0.9 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 234 | ±1.4 % |
| S3Scan | hardwoodWideFilteredScan | 310 | ±0.3 % |
