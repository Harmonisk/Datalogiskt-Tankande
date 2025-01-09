# Högt eller lågt

## Högt eller lågt

Fråga användaren efter ett tal mellan 1 och 100. Programmet ska ha ett hemligt tal sparat. Det ska fortsätta fråga användaren till dess att användaren gissar det hemliga talet. Om man gissade för högt eller för lågt så ska det skrivas ut, så att användaren har en rimlig chans att klara det.

## Decomposition

1. slumpa fram ett tal
    1. fråga om tal tills spelaren gissar rätt
        1. om för högt skriv ut att talet är lägre
        2. om för lågt skriv ut att talet är högre        

## Pattern recognition

loop 1.
input 1.
selektion 1.
output 1.1, 1.1.1, 1.1.2

## Abstraction

* slumpa fram tal
* fråga om tal
* jämför svar
* ge feedback på gissning

## Algorithm design

1. skapa en rättgissningsvariabel och sätt den till ett slumpmässigt värde i spannet 1-100
2. skapa en rättgissningsflagga och sätt den till false
3. gör följande så länge rättgissningsflaggan är false
    1. låt spelaren mata in en gissning lägg den i en ny gissningsvariabel
    2. jämför gissingsvariabeln med rättgissningsvariabeln
        1. om de är lika sätt rättgissningsflaggan till true
        2. om gissningsvariabeln är lägre än rättgissningsvariabeln skriv ut att svaret är högre
        3. om gissningsvariablen är högre än rättgissingsvariablen skriv ut att svaret är lägre