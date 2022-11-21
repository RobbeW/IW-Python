**Opgave:**

**Het vermoeden van Collatz**


Voorspel de uitvoer van volgend programma: 
(noteer als: uitvoer = 'antwoord') 

```
a = 28
print ('Vermoeden van Collatz')
while a != 1: 
  print(a, end=" ")
  if a/2 == int(a/2) :
    a = int(a/2) 
  else: 
    a = int(a * 3 + 1)
print(a)
print("stop")
````
