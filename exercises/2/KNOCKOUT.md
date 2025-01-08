# Knockout

* Spelet har 2st tärningar.
* Du som spelare väljer ett “knock out number” – antingen 6, 7, 8, eller 9.
* Du som spelare väljer också vilken poäng som skall uppnås för att spelet skall avslutas.
* Spelaren kastar båda tärningarna. Anteckna varje kasts resultat.
* Om spelaren kastar det angivna "knock out number" så ges minuspoäng

## Decomposition

1. skapa två tärningar
	1. 1. sätt ett spann 1-6
2. välj ett av 6,7,8 eller 9
	2.1. läs in input
	2.2. kolla att siffran är giltig
3. välj poäng
	3.1. läs in input
4. kasta tärningar
	4. 1. generera slumptal i spannet
	4. 2. logga kastresultatet
		4. 2. 1. skapa samling
			4. 2. 1. 1. (som kan logga två tärningar per kast?)
	4. 3. kolla om resultatet är samma som knock out number
		4. 3. 1. isådantfall ge minuspoäng
		4. 3. 2. annars ge pluspoäng
5. om poäng är lika med eller större än slutpoäng avsluta spelet

## Pattern recognition

* skapa samlingar 2, 4.2.1, 4.2.1.1
* skapa variabler 1.1x2, 2.1, 4.1 
* läs input 2.1, 3.1
* jämför siffror 2.2, 4.3
* selektion 2.2, 4.3

## Abstraction

* läs in k.o.n.
* läs in poäng
* slumpa kast
* logga kast
* ge plus- eller minuspoäng

## Algorithm design

1. skapa samling med tillåtna nummer
2. skapa variabel för inläsning av k.o.n.
3. skapa flagga(bolean) för korrekt inläsning och sätt den till false
4. gör följande så länge flaggan är false
	4. 1. läs in spelarens val av k.o.n. så
	4. 2. jämför med listan av tillåtna nummer
		4. 2. 1. om tillåtet sätt flaggan till true
		4. 2. 2. annars ge felmeddelande
5. skapa variabel för inläsning av slutpoäng
	5. 1. läs in slutpoäng
6. skapa samling för loggning av kast som består av samlingar med två nummer
7. skapa variabel för nuvarande poängställning och sätt den till 0  
8. gör följande så länge poängställningen är mindre än slutpoängen:
	8. 1. slumpa fram två tal i spannet 1-6 och logga båda i samma underlista i listan
	8. 2. skapa en variabel som är summan av de två tärningarna i det senast loggade kastet
	8. 3. jämför summan med k.o.n.
		8. 2. 1. om talet är samma subtrahera summan från poängställningen
		8. 2. 1. annars addera summan till poängställningen