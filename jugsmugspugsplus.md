## Write a program that receives a number on the input.

  - If the number is a multiple of 3, or it contains digit 3, it prints "Jugs". 
  - If the number is a multiple of 5, or it contains digit 5, it prints "Mugs".
  - If the number is a multiple of 7, or it contains digit 7, it prints "Pugs".

Otherwise, it prints the number.

SPECIAL REQUIREMENT: 
Try and limit the number of conditional statements to not more than 4. 
And use only one print statement.

```
n = int(input())
if(n % 3 == 0 or '3' in str(n)):
  print("Jugs")
if(n % 5 == 0 or '5' in str(n)):
  print("Mugs")
if(n % 7 == 0 or '7' in str(n)):
  print("Pugs")

```

```
INPUT 
73 
OUTPUT
JugsPugs

INPUT 
51  

OUTPUT
JugsMugs


INPUT 
105

OUTPUT 
JugsMugsPugs


```
