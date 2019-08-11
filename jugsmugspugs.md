## Write a program that receives a number on the input.
If the number is a multiple of 3, it prints "Jugs". 
If the number is a multiple of 5, it prints "Mugs".
If the number is a multiple of 7, it prints "Pugs".

If the number is a multiple of both 3 and 5, it prints "JugsMugs".
If the number is a multiple of both 3 and 7, it prints "JugsPugs".
If the number is a multiple of both 5 and 7, it prints "MugsPugs".
If the number is a multiple of both 3, 5 and 7, it prints "JugsMugsPugs".

```
a = int(input())
if ((a % 3 == 0) and (a % 5 == 0) and (a % 7 == 0)):
  print("jugsmugspugs")
elif a % 3 ==0 and a % 5 == 0:
  print("jugsmugs")
elif a % 3 == 0 and a % 7 == 0:
  print("jugspugs")
elif a % 5 == 0 and a % 7 == 0 :
  print("mugspugs")
elif a % 3 == 0:
  print("jugs")
elif a % 5 == 0:
  print("mugs")
elif a % 7 == 0:
  print("pugs")
else :
  print (a)

```
```
INPUT 
15

OUTPUT
JugsMugs

INPUT 
21

OUTPUT
JugsPugs


INPUT 
105

OUTPUT 
JugsMugsPugs

```
