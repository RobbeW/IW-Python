# Oefening 12 -  De Functie van X 

**Gegeven:**

De functie *f* met *f*(x) = 7x - 13. 
Dit kan je ook lezen als: 
```
y = 7*x - 13
```


**Opgave:**

* Schrijf een programma dat naar een x-waarde vraagt
* Print de bijbehorende functiewaarde of y-waarde print naar het scherm.
* Je start met volgende code. Vul deze verder aan waar dit gevraagd is! 
* De rest van de code neem je over. 

```
#Input - We vragen naar de waarde van x
x = ... #VUL AAN

#Berekening
#f(x), de functiewaarde van X heet ook wel: y
y = ... #VUL AAN

#Output
print(...) #VUL AAN


#De code hieronder neem je over en moet je nog niet kennen of kunnen. 
X = [x-2, x-1, x, x+1, x+2]
Y=[]
for i in X: 
  y = 7*x -13 
  Y.append(y)
import matplotlib.pyplot as plt
plt.plot(X, Y)
plt.ylabel('f(x) = 7x-13')
plt.show()

