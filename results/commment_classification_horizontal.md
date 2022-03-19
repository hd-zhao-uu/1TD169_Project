# Comment classification

## Strong Scaling
The dataset is RC_2011-07, which has 10,557,466 JSON objects.
|  workers   | 100,000 JSON Objects |  200,000 JSON Objects | 400,000 JSON Objects |
| ----       | ----                 |----                     | ----  |
|  1         |    251.257            |   464.337            | 896.094 |
|  2         |     134.301        |     247.702            |  495.681    |
|  3         |    103.986            |       205.003       |  306.770    |
|  4         |    101.205             |         150.905             |    299.870          |


## Weak Scaling
The dataset is RC_2012-12.
|  workers   | 100,000 JSON Objects/node |  200,000 JSON Objects/node | 400,000 JSON Objects/node |
| ----       | ----                      |      ----                    | ----                      |
|  1         |   334.715              |      548.89                    |      980.263|
|  2         |    306.501             |       506.186             |    912.414 |
|  3         |   301.507        |   499.206       |  894.589    |   
| 4          |   306.706                |   490.128            |    909.649          |