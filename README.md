# simple-charts
Experimenting with the Peity chart library found at http://benpickles.github.io/peity

The data is generates using Spark SQL on numeric columns:

```
SELECT histogram_numeric(<col name>,50)
FROM t1
```
