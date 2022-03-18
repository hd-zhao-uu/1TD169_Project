# Comment classification

## Strong Scaling
The dataset is RC_2011-07, which has 10557466 JSON objects.
|  core   | 1GB Memory | 2GB Memory      |3GB Memory        |
|  ----   | ----   |----             | ----  |
| 1       |  4411.083s     | 4521.225s               | 4477.356s     |
| 2       |  2352.731s     | 2321.320s               | 2341.975s      |
| 4       |  1210.510s    |1211.181s              | 1217.717s     |
| 8       |  627.181s     |632.777s               | 632.496s     |

---

## Weak Scaling
Each processor will handle 250,000 JSON objects, 3GiB memory each core.
| Data Size   |  Cores   | Time  |
|  ----       |  ----    | ----  |
|   250,000   | 1        |    283.75s   |
|   500,000   | 2        |    237.22s   |
| 1,000,000   | 4        |    200.67s   |
| 2,000,000   | 8        |    179.45s   |

Each processor will handle 500,000 JSON objects, 3GiB memory each core
| Data Size   |  Cores   | Time  |
|  ----       |  ----    | ----  |
|   500,000   | 1        |    360.279s   |
|  1,000,000  | 2        |    346.021s   |
| 2,000,000   | 4        |    349.214s   |
| 4,000,000   | 8        |    289.746s   |