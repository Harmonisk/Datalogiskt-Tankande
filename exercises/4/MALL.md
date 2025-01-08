# Sten, sax och påse

## Decomposition

1. varje spelare väljer ett av sten, sax och påse
2. jämför spelarnas val
    2. 1. om samma typ gör inget
    2. 1. annars ge vinsten till rätt spelare
3. kom ihåg antalet vinster per spelare
4. avsluta när en spelare nått 3 vinster

## Pattern recognition

* skapa variabler 
* spara variabler

## Abstraction

* välj drag
* jämför
* tilldela vinst om ej lika
* avsluta efter 3 vinster

## Algorithm design

1. definiera sten, sax och påse som 1,2 respektive 3
2. definiera vinsträkningsvariabler för båda spelarna och sätt dem till noll
3. definiera dragvariabel för båda spelarna
4. gör följande tills spelare etts vinsräkningsvariabel är lika med 3 eller tills spelare tvås vinsträkningsvariable är lika med tre:
    4. 1. gör detta två gånger:
        4. 1. 1. låt en spelare som ej definierat sitt drag välja sitt drag
        4. 1. 2. lagra draget i spelarens dragvariabel
    4. 2. jämför spelarnas drag
        4. 2. 1. om lika gör inget
        4. 2. 2. annars gör följande:
            4. 2. 2. 1. om differensen mellan spelare ett och spelare tvås tal är -1 plussa på spelare etts vinsträknare med 1
            4. 2. 2. 2. annars plussa på spelare tvås vinstvariabel med två
    