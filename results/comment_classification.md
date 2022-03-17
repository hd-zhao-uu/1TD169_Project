# Comment classification

## Strong Scaling
The datasize is RC_2011-07
|  core   | time  |
|  ----   | ----  |
| 1       |  4477.356s     |
| 2       |  2341.975s      |
| 4       |  1217.717s     |
| 8       |  632.496s     |

---

## Weak Scaling
Each processor will handle 250,000 JSON objects, 3GiB memory each core.
| Data Size   |  Cores   | Time  |
|  ----       |  ----    | ----  |
|   250,000   | 1        |    283.75s   |
|   500,000   | 2        |    237.22s   |
| 1,000,000   | 4        |    200.67s   |
| 2,000,000   | 8        |    179.45s   |