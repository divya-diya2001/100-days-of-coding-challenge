## Given the year number. You need to check if this year is a leap year. If it is, print LEAP, otherwise print COMMON.

```
# Read an integer:
a = int(input())
if (a%4==0 and a%100!=0 or a%400==0):
# print a value:
  print("LEAP")
else:
  print("COMMON")

```
```
Example input
2012

Example output
LEAP

```
