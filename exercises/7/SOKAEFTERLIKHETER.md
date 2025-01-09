# Söka efter likheter mellan ord

## Högt eller lågt

Fråga användaren efter två ord, och kontrollera därefter hur många bokstäver som förekommer på samma plats i båda orden. 

## Decomposition

1. fråga användaren efter två ord
    1. fråga efter ord ett
    2. lagra ord ett
    3. fråga efter ord två
    4. lagra ord två
2. gå igenom varje bokstav i det första ordet
    1. för varje bokstav jämför den med bokstaven på samma position i det andra ordet
    2. om de är lika räkna det

## Pattern recognition

* input: 1.1, 1.3
* skapa variabler: 1.2, 1.4, 2.2
* loopar: 2

## Abstraction

* fråga om två ord
* jämför bokstäver på samma position
* räkna fallen då de är lika

## Algorithm design

1. skapa en variabel för det första ordet
2. skapa en variabel för det andra ordet
3. be användaren mata in första ordet och lagra det i den första variabeln
4. be användaren mata in det andra ordet och lagra det i den andra variabeln
5. skapa en räknevariabel för antal matchhningar och sätt den till noll
6. skapa en variabel för position i orden och sätt den till noll
7. skapa en storleksvariabel
8. jämför längden på orden och sätt storleksvariabeln till storleken på det minsta ordet
9. medans uppräkningsvariabeln är mindre än storleksvariabeln gör följande:
    1. jämför tecknet på positionen indexerat med uppräkningsvariabeln i båda orden
        1. om de är lika räkna upp matchningsvariabeln med ett
    2. räkna upp positionsvariabeln med ett

