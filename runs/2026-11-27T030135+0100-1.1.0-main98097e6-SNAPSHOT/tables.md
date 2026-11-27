| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| Filter | hardwoodDefault[matchAll] | 17.6 | ±0.3 % |
| Filter | hardwoodDefault[selective] | 5.43 | ±0.7 % |
| Filter | hardwoodRowReader[matchAll] | 38.8 | ±0.3 % |
| Filter | hardwoodRowReader[selective] | 6.03 | ±1.1 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| BloomFilter | hardwoodBloom[absent] | 0.402 | ±0.8 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| TimeWindow | hardwoodColumnFiltered[last25pct] | 14.5 | ±1.3 % |
| TimeWindow | hardwoodRowFiltered[last25pct] | 28.0 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| DictionaryFilter | hardwoodRowIn | 10.1 | ±0.5 % |
| DictionaryFilter | hardwoodRowLtWide | 42.9 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| OneBrc | hardwoodColumnIds | 1,315 | ±0.8 % |
| OneBrc | hardwoodColumnSplits | 493 (not settled) | ±0.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| BinaryScan | hardwoodColumnViews | 220 | ±0.9 % |
| BinaryScan | hardwoodRowStrings | 997 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NestedScan | hardwoodRowReaderTyped | 164 | ±2.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NestedColumnScan | hardwoodColumnReaders | 2,842 | ±1.7 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FlatScan | columnarDrain | 148 | ±1.3 % |
| FlatScan | hardwoodColumnar | 275 | ±0.9 % |
| FlatScan | hardwoodRowReaderIndexed | 419 | ±1.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| NarrowScan | hardwoodColumnar | 93.6 | ±1.4 % |
| NarrowScan | hardwoodRowReaderIndexed | 169 | ±0.5 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| WideScan | hardwoodColumnar | 357 | ±1.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FixedSizeListScan | columnFast[768] | 12.4 | ±0.3 % |
| FixedSizeListScan | rowFast[768] | 19.5 | ±0.3 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| Write | hardwoodColumnar[ZSTD] | 101 | ±1.2 % |
| Write | hardwoodRow[ZSTD] | 269 | ±0.9 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| FloatEncoding | hardwoodRead[ZSTD][ALP] | 32.2 | ±0.1 % |
| FloatEncoding | hardwoodRead[ZSTD][BYTE_STREAM_SPLIT] | 70.5 | ±1.2 % |
| FloatEncoding | hardwoodWrite[ZSTD][ALP] | 109 | ±0.3 % |
| FloatEncoding | hardwoodWrite[ZSTD][BYTE_STREAM_SPLIT] | 202 | ±0.1 % |
| Benchmark | Contender | 1.1.0-main98097e6-SNAPSHOT ms | 1.1.0-main98097e6-SNAPSHOT spread |
|---|---|---:|---:|
| S3Scan | hardwoodFixedSizeBloomLookup | 307 | ±1.2 % |
| S3Scan | hardwoodLargeBloomLookup | 109 | ±0.9 % |
| S3Scan | hardwoodMultiFileScan | 490 | ±3.7 % |
| S3Scan | hardwoodProjectedScan | 174 | ±1.0 % |
| S3Scan | hardwoodRemoteBesideWideRemote | 250 | ±3.1 % |
| S3Scan | hardwoodWideFilteredScan | 310 | ±0.8 % |
