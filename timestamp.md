## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.

```
hr1 = int(input())
min1 = int(input())
sec1 = int(input())
hr2 = int(input())
min2 = int(input())
sec2 = int(input())
total1 = hr1 * 3600   + min1 * 60 + sec1 
total2 = hr2 * 3600  + min2 * 60 + sec2 
print(total2 - total1)

```

```
Example input 
1
1
1
2
2
2

Example output 
3661

```
