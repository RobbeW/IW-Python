# Oefening 7: Het Koeriersbedrijf 

**Gegeven:** 

Een koeriersbedrijf hanteert volgende regels voor het bepalen van de prijs van een pakje: 

* basisprijs: 2.00 euro
* extra per **begonnen** 20 gram: 0.40 euro
* extra per **begonnen** 10 km: 0.30 euro

Om een pakje van 68 gram (=massa) 102 km (=afstand) ver te versturen, betaal je: 

```
startprijs + 4*0.40 + 11*0.30

of 

(2.00 + 4 * 0.40 + 11 * 0.30) euro = 6.90 euro
```


**Gevraagd:**

Schrijf een programma dat die prijs onmidellijk berekent. 
* Begin jouw code met **import math**
* Vraag naar de massa van het pakje; 
* Vraag naar de afstand; 
* Naar boven afronden: **math.ceil(x)**
* Print de prijs op het scherm met een verzorgde volzin! 

