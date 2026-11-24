| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.9 | ±0.3 % |
| Filter | hardwoodDefault[selective] | 5.50 | ±0.5 % |
| Filter | hardwoodRowReader[matchAll] | 39.2 | ±0.4 % |
| Filter | hardwoodRowReader[selective] | 6.89 (not settled) | ±1.2 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.398 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.7 | ±0.8 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.6 (bimodal) | ±9.7 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 45.9 | ±2.6 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,306 | ±0.2 % |
| OneBrc | hardwoodColumnSplits | 493 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 224 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 1,003 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 166 | ±1.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,783 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 272 | ±0.9 % |
| FlatScan | hardwoodRowReaderIndexed | 435 | ±3.8 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 92.3 | ±0.8 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 104 | ±1.3 % |
| Write | hardwoodRow[ZSTD] | 320 | ±0.4 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.5 | ±3.4 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 69.6 | ±0.6 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±0.6 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main25e397d-SNAPSHOT ms | 1.1.0-main25e397d-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 308 | ±0.8 % |
| S3Scan | hardwoodLargeBloomLookup | 111 | ±0.7 % |
| S3Scan | hardwoodMultiFileScan | 469 | ±3.1 % |
| S3Scan | hardwoodProjectedScan | 175 | ±0.5 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 243 | ±1.0 % |
| S3Scan | hardwoodWideFilteredScan | 310 | ±0.7 % |
