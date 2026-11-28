| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.6 | ±0.4 % |
| Filter | hardwoodDefault[selective] | 5.22 | ±2.8 % |
| Filter | hardwoodRowReader[matchAll] | 39.0 | ±0.6 % |
| Filter | hardwoodRowReader[selective] | 6.10 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.401 | ±2.5 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.6 | ±0.8 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.0 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 42.5 | ±3.5 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,314 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 501 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 223 | ±0.7 % |
| BinaryScan | hardwoodRowStrings | 999 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 168 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,822 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 150 | ±0.2 % |
| FlatScan | hardwoodColumnar | 274 | ±0.7 % |
| FlatScan | hardwoodRowReaderIndexed | 440 | ±3.2 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 93.9 | ±0.8 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 358 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.6 | ±1.1 % |
| FixedSizeListScan | rowFast[768] | 19.8 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 | ±1.1 % |
| Write | hardwoodRow[ZSTD] | 266 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.5 | ±0.7 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.6 | ±0.6 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 110 | ±0.4 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main7dcb71f-SNAPSHOT ms | 1.1.0-main7dcb71f-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 305 | ±1.6 % |
| S3Scan | hardwoodLargeBloomLookup | 111 | ±1.8 % |
| S3Scan | hardwoodMultiFileScan | 502 | ±5.8 % |
| S3Scan | hardwoodProjectedScan | 175 | ±0.6 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 239 | ±0.8 % |
| S3Scan | hardwoodWideFilteredScan | 309 | ±0.6 % |
