# Going to Boston

Spelet har 3st tärningar.

1. Kasta tärningarna och spara tärningen med högsta värdet.
2. Kasta de kvarvarande 2 och spara tärningen med högsta värdet.
3. Kasta sista tärningen och summera samtliga tre tärningar.
4. Spelaren med högst summerat värde vinner. Max poäng är 18.

## Decomposition

1. skapa 3 tärningar
2. kasta 3 tärningar
    1. spara högsta tärningen i en lista
3. kasta 2 tärningar
    1. spara högsta tärningen i en lista
3. kasta 1 tärning
    1. addera värdet på tärningen till värdet på de två sparade tärningarna

## Pattern recognition

* slumpa tal: 2, 3, 4
* sortera ut högsta talet: 2.1, 3.1  

## Abstraction

* kasta tärningar
* välj ut högsta
* kasta om med en färre tärning
* addera alla högsta kast

## Algorithm design

1. skapa ett spann 1-6
2. skapa en tärningsräkningsvariabel och sätt den till 3
3. skapa en lista för högsta kast
4. gör följande tills tärningsräkningsvariabeln är 0:
    1. skapa en högsta kastvariabel och sätt den till 0
    2. gör följande lika många gånger som tärningsräkningsvariabeln:
        1. generera ett tal i spannet
        2. om talet är högre än högsta kastvariabeln byt ut högsta kastvariabeln mot talet
    3. addera högsta kastvariabeln till listan för högsta kastaa
5. summera alla talen i högsta kastlistan