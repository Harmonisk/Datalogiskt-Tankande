# Fizzbuzz

Loopa igenom hundra nummer och om:

* Numret är dividerbart med 3, skriv ut "Fizz"
* Numret är dividerbart med 5, skriv ut "Buzz"
* Numret är dividerbart med 3 och 5, skriv ut "FizzBuzz"

## Decomposition

1. skapa loop som går från 1-100
    1. i varje iteration räkna upp
    2. kolla om talet är delbart med 3 och skrev i sådant fall ut "Fizz"
    3. kolla sedan om talet är delbart med 5 och skriv ut "Buzz"
    4. byt rad

## Pattern recognition

modulus: 1.2, 1.3
skriv ut text: 1.2, 1.3, 1.4

## Abstraction

* loopa 1-100
* modulus med 5 och 3
* skriv ut rätt string vid rest 0

## Algorithm design

1. skapa en loopräkningsvariabel och sätt den till 1
2. medans loopräkningsvariabeln är mindre än 100:
    1. gör modulus på l.r.v:en med 3
    2. om resten är 0 skriv ut "Fizz" utan radbrytning
    3. gör modulus på l.r.v:en med 5
    4. om resten är 0 skriv ut "Buzz" utan radbrytning
    5. byt rad
