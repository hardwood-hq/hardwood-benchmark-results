| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.4 % |
| Filter | hardwoodDefault[selective] | 5.90 | ±1.3 % |
| Filter | hardwoodRowReader[matchAll] | 39.9 | ±0.1 % |
| Filter | hardwoodRowReader[selective] | 6.99 (not settled) | ±0.9 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.391 | ±1.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 15.9 | ±0.5 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.2 | ±2.5 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 31.6 | ±0.1 % |
| DictionaryFilter | hardwoodRowLtWide | 65.9 (not settled) | ±3.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,330 | ±0.5 % |
| OneBrc | hardwoodColumnSplits | 537 (not settled) | ±0.1 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 223 | ±1.5 % |
| BinaryScan | hardwoodRowStrings | 996 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 149 | ±1.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,825 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 290 | ±0.2 % |
| FlatScan | hardwoodRowReaderIndexed | 416 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 121 | ±0.6 % |
| NarrowScan | hardwoodRowReaderIndexed | 180 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±0.3 % |
| Write | hardwoodRow[ZSTD] | 300 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 35.0 (not settled) | ±0.7 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 102 (bimodal) | ±12.9 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 121 | ±0.5 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 208 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5f5b27b-SNAPSHOT ms | 1.1.0-main5f5b27b-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 309 | ±1.7 % |
| S3Scan | hardwoodLargeBloomLookup | 113 | ±2.5 % |
| S3Scan | hardwoodMultiFileScan | 516 | ±7.5 % |
| S3Scan | hardwoodProjectedScan | 184 | ±0.6 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 256 | ±2.6 % |
| S3Scan | hardwoodWideFilteredScan | 313 | ±1.4 % |
