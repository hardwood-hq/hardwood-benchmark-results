| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.0 | ±0.5 % |
| Filter | hardwoodDefault[selective] | 5.71 | ±0.5 % |
| Filter | hardwoodRowReader[matchAll] | 38.9 | ±0.6 % |
| Filter | hardwoodRowReader[selective] | 6.88 (not settled) | ±0.9 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.399 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.8 | ±0.5 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 29.0 (bimodal) | ±10.2 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.2 % |
| DictionaryFilter | hardwoodRowLtWide | 46.1 | ±3.7 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,314 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 492 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 223 | ±0.1 % |
| BinaryScan | hardwoodRowStrings | 998 | ±1.0 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 164 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,873 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | hardwoodColumnar | 271 | ±1.3 % |
| FlatScan | hardwoodRowReaderIndexed | 443 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 92.8 | ±1.1 % |
| NarrowScan | hardwoodRowReaderIndexed | 168 | ±0.0 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 102 | ±0.9 % |
| Write | hardwoodRow[ZSTD] | 313 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 31.2 | ±2.6 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.1 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 108 | ±0.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 203 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main5c42836-SNAPSHOT ms | 1.1.0-main5c42836-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 306 | ±1.5 % |
| S3Scan | hardwoodLargeBloomLookup | 112 | ±2.0 % |
| S3Scan | hardwoodMultiFileScan | 500 | ±7.2 % |
| S3Scan | hardwoodProjectedScan | 176 | ±0.7 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 242 | ±3.5 % |
| S3Scan | hardwoodWideFilteredScan | 311 | ±0.9 % |
