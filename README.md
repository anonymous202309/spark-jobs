# Spark Jobs

Typical Spark jobs for evaluation purposes.

Available Spark jobs (including dataset generators):

| Data Type |  Algorithm
| --- | ---
| Vector | KMeans |
| Vector | LinearRegression |
| Vector | LogisticRegression |
| Tabular | GroupByCount |
| Tabular | Join | Spark |
| Tabular | SelectWhereOrderBy |
| Text | Grep |
| Text | Sort |
| Text | WordCount |

## Compilation

To compile the jobs to a jar file:

```bash
cd spark
sbt package
```

