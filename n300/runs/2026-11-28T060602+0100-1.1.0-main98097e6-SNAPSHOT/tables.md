| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 18.0 | ±0.2 % |
| Filter | hardwoodDefault[selective] | 5.34 | ±3.6 % |
| Filter | hardwoodRowReader[matchAll] | 39.0 | ±0.7 % |
| Filter | hardwoodRowReader[selective] | 6.12 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.401 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.9 | ±1.4 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.0 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±1.1 % |
| DictionaryFilter | hardwoodRowLtWide | 43.8 | ±1.6 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,306 | ±0.4 % |
| OneBrc | hardwoodColumnSplits | 498 (not settled) | ±0.1 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 226 | ±0.8 % |
| BinaryScan | hardwoodRowStrings | 1,000 | ±0.7 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 166 | ±1.8 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,876 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 148 | ±1.3 % |
| FlatScan | hardwoodColumnar | 274 | ±1.2 % |
| FlatScan | hardwoodRowReaderIndexed | 417 | ±2.2 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 93.6 | ±0.8 % |
| NarrowScan | hardwoodRowReaderIndexed | 170 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 370 | ±1.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.7 | ±0.2 % |
| FixedSizeListScan | rowFast[768] | 19.7 | ±0.2 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 102 | ±1.8 % |
| Write | hardwoodRow[ZSTD] | 270 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.7 | ±0.1 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.5 | ±0.1 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 110 | ±1.9 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 204 | ±0.6 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 307 | ±1.1 % |
| S3Scan | hardwoodLargeBloomLookup | 112 | ±1.4 % |
| S3Scan | hardwoodMultiFileScan | 477 | ±6.3 % |
| S3Scan | hardwoodProjectedScan | 176 | ±0.9 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 242 | ±0.3 % |
| S3Scan | hardwoodWideFilteredScan | 312 | ±1.6 % |
