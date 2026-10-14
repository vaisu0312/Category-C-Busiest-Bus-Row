# Category C — Busiest Bus Row

Java solution for Problem 10.

## How it works
- The outer loop visits each row.
- The inner loop adds the number of students in that row.
- The best row is updated only when a strictly larger total is found, so ties keep the smaller row index.

## Sample output
```text
Row 1, Total 7
```

## Complexity
- Time: O(r * c), where r is the number of rows and c is the number of columns.
- Additional space: O(1), excluding the returned two-element array.

## Run
```text
javac BusiestBusRow.java
java BusiestBusRow
```
