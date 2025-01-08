# Stegen

Ett tärningspel där användaren ska kasta 1st tärning. Vid första kastet ska målet vara 1. Om 1 ej fås, ska man försöka igen. Hur många kast tar det för att komma upp i en stege, 1,2,3,4,5,6? Antal kast måste räknas.

## Decomposition

* skapa funktion för tärningsslag
	* skapa tärning
	* slumpa fram nummer
* logga antal slag
* kolla om slag är rätt siffra
* hålla reda på vilken siffra man uppnått

## Pattern recognition

* jämföra siffror
* logga siffror

## Abstraction

* räkna kast
* slumpa kast
* jämför kast
* börja om eller räkna upp

## Algorithm design

1. sätt ett spann 1-6
2. sätt en räknevariabel till noll
3. sätt en platsvariabel till ett
4. tills platsvariabeln är lika med 6 gör följande: 
	1. räkna upp räknevariabeln med ett
	2. generera ett slumpmässigt tal inom spannet
	3. jämför det slumpmässigt genererade talet med platsvariabeln
		1. om det är samma tal
			1. räkna upp platsvariabeln med ett
		2. om det inte är samma tal
			1. sätt platsvariabeln till 1
5. skriv ut räknevariabeln