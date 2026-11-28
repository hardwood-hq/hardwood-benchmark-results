| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.0 | ±1.7 % |
| Filter | hardwoodDefault[selective] | 5.12 | ±3.9 % |
| Filter | hardwoodRowReader[matchAll] | 38.6 | ±0.2 % |
| Filter | hardwoodRowReader[selective] | 6.61 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.402 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.6 | ±0.6 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.0 | ±3.8 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.0 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 43.2 | ±2.0 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,305 | ±0.1 % |
| OneBrc | hardwoodColumnSplits | 497 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 221 | ±0.1 % |
| BinaryScan | hardwoodRowStrings | 1,011 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 172 | ±2.0 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,870 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 149 | ±1.8 % |
| FlatScan | hardwoodColumnar | 278 | ±0.5 % |
| FlatScan | hardwoodRowReaderIndexed | 436 | ±1.9 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 92.6 | ±2.1 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 44,096 | ±5.7 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.4 | ±0.1 % |
| FixedSizeListScan | rowFast[768] | 19.6 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 102 | ±0.9 % |
| Write | hardwoodRow[ZSTD] | 313 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.5 | ±0.3 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.7 | ±0.4 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 109 | ±0.8 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 201 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 310 | ±0.7 % |
| S3Scan | hardwoodLargeBloomLookup | 111 | ±1.4 % |
| S3Scan | hardwoodMultiFileScan | 479 | ±7.1 % |
| S3Scan | hardwoodProjectedScan | 176 | ±1.1 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 245 | ±4.2 % |
| S3Scan | hardwoodWideFilteredScan | 311 | ±1.4 % |
