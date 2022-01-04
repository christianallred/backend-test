## Backend Skills Tests

Implement an API.

You can use any framework or packages you like. 

- The first end point should accept a CSV file and parse the data into SOME storage mechanism (in memory would be fine).
- The second endpoint should allow the fetching of any row of that data by guid, or email. 
- The third endpoint should return the average, median, min, and max income for all rows with income values. you can return it as follows

```
{
    average: number
    median: number
    min: number
    max: number
    sum: number
}
```

