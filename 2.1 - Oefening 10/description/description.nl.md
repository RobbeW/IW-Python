**Gegeven:**

Bij het betalen van een bedrag in euro's, kunnen verschillende soorten biljetten en munten worden gebruikt. Om het aantal biljetten en munten te bepalen dat nodig is om een bepaald bedrag te betalen, moet je het bedrag eerst opdelen in biljetten en munten van verschillende waardes.

**Gevraagd:**

* Vraag aan de gebruiker om het te betalen bedrag in euro's in te voeren.
* Bepaal het aantal biljetten van 50 euro dat nodig is om het bedrag te betalen met behulp van de volgende code:

```
bedrag = int(input("Voer het te betalen bedrag in euro's in: "))

aantal_vijftig = bedrag // 50
bedrag %= 50
```

* Gebruik deze code als basis en breid deze uit met het bepalen van het aantal biljetten van 20, 10 en 5 euro, en het aantal munten van 2 en 1 euro dat nodig is om het bedrag te betalen. Gebruik dezelfde notatie als in de bovenstaande code voor het bepalen van het aantal biljetten en munten.

* Print het totale aantal biljetten en munten dat nodig is om het bedrag te betalen in de volgende vorm: "U hebt [aantal_vijftig] biljetten van 50 euro, [aantal_twintig] biljetten van 20 euro, [aantal_tien] biljetten van 10 euro, [aantal_vijf] biljetten van 5 euro, [aantal_twee] munten van 2 euro en [aantal_een] munten van 1 euro nodig om het bedrag te betalen."

* Voer tests uit met verschillende bedragen, zoals 100 euro, 73 euro, 37 euro, enzovoort. Zorg ervoor dat de code correct werkt en het juiste aantal biljetten en munten weergeeft.

* Vergeet niet om te **debuggen** en eventuele fouten op te lossen.

