| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.1 % |
| Filter | hardwoodDefault[selective] | 5.55 (bimodal) | ±6.1 % |
| Filter | hardwoodRowReader[matchAll] | 39.1 | ±0.3 % |
| Filter | hardwoodRowReader[selective] | 6.97 (not settled) | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.394 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 (not settled) | ±1.0 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.5 | ±2.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.6 % |
| DictionaryFilter | hardwoodRowLtWide | 45.7 | ±2.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,315 | ±1.0 % |
| OneBrc | hardwoodColumnSplits | 494 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 220 | ±1.1 % |
| BinaryScan | hardwoodRowStrings | 998 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 165 | ±1.2 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,861 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 272 | ±0.7 % |
| FlatScan | hardwoodRowReaderIndexed | 430 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 91.1 | ±0.3 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 103 | ±0.5 % |
| Write | hardwoodRow[ZSTD] | 312 | ±1.8 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.3 | ±1.4 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.0 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±1.0 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 308 | ±1.9 % |
| S3Scan | hardwoodLargeBloomLookup | 112 | ±2.0 % |
| S3Scan | hardwoodMultiFileScan | 501 | ±6.9 % |
| S3Scan | hardwoodProjectedScan | 176 | ±1.9 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 245 | ±3.7 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±0.3 % |
