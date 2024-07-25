# Estructuras de Control

En programación, las estructuras de control nos permiten tomar decisiones y repetir tareas. A continuación, veremos cómo funcionan algunas de las estructuras de control más comunes utilizando pseudocódigo en PSeInt.

## Condicional Simple

La estructura de control condicional simple nos permite ejecutar un bloque de código si se cumple una condición determinada. En PSeInt, la sintaxis es la siguiente:

```
Si condicion Entonces
    // bloque de codigo si la condicion es verdadera
FinSi
```

Ejemplo en PSeInt:
```
edad <- 18
Si edad >= 18 Entonces
    Escribir("Eres mayor de edad")
FinSi
```

## Condicional Bicondicional (Si-Sino)

La estructura de control condicional bicondicional nos permite ejecutar un bloque de código si se cumple una condición y otro bloque de código si no se cumple. En PSeInt, la sintaxis es la siguiente:

```
Si condicion Entonces
    // bloque de codigo si la condicion es verdadera
Sino
    // bloque de codigo si la condicion es falsa
FinSi
```

Ejemplo en PSeInt:
```
edad <- 16
Si edad >= 18 Entonces
    Escribir("Eres mayor de edad")
Sino
    Escribir("Eres menor de edad")
FinSi
```

## Condicional Múltiple (Según-Caso)

La estructura de control condicional múltiple nos permite evaluar múltiples condiciones y ejecutar el bloque de código correspondiente a la primera condición verdadera. En PSeInt, la sintaxis es la siguiente:

```
Segun variable Hacer
    Caso valor1:
        // bloque de codigo si la variable es igual a valor1
    Caso valor2:
        // bloque de codigo si la variable es igual a valor2
    OtroCaso:
        // bloque de codigo si no se cumple ninguna de las condiciones anteriores
FinSegun
```

Ejemplo en PSeInt:
```
dia <- "Lunes"
Segun dia Hacer
    Caso "Lunes":
        Escribir("Es el primer día de la semana")
    Caso "Viernes":
        Escribir("Es el último día de la semana")
    OtroCaso:
        Escribir("Es un día intermedio de la semana")
FinSegun
```

## Ciclo Para

El ciclo para nos permite repetir un bloque de código un número específico de veces. En PSeInt, la sintaxis es la siguiente:

```
Para variable <- valorInicial Hasta valorFinal Con paso incremento Hacer
    // bloque de codigo a repetir
FinPara
```

Ejemplo en PSeInt:
```
Para i <- 1 Hasta 5 Con paso 1 Hacer
    Escribir(i)
FinPara
```

## Ciclo Mientras

El ciclo mientras nos permite repetir un bloque de código mientras se cumpla una condición específica. En PSeInt, la sintaxis es la siguiente:

```
Mientras condicion Hacer
    // bloque de codigo a repetir
FinMientras
```

Ejemplo en PSeInt:
```
numero <- 0
Mientras numero < 

5 Hacer
    Escribir(numero)
    numero <- numero + 1
FinMientras
```

## Ciclo Hacer Mientras

El ciclo hacer mientras nos permite repetir un bloque de código al menos una vez y luego continuar haciéndolo mientras se cumpla una condición específica. En PSeInt, la sintaxis es la siguiente:

```
Hacer
    // bloque de codigo a repetir
Mientras condicion
```

Ejemplo en PSeInt:
```
numero <- 0
Hacer
    Escribir(numero)
    numero <- numero + 1
Mientras numero < 5
```