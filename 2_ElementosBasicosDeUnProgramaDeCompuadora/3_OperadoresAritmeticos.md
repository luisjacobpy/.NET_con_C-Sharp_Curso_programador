# Operadores aritmeticos

En C#, los operadores aritméticos son símbolos especiales que se utilizan para realizar operaciones matemáticas en variables y valores numéricos. Estos operadores permiten realizar diversas operaciones, como suma, resta, multiplicación, división, entre otros. A continuación, te mostraré los operadores aritméticos básicos en C# y cómo funcionan:

## Suma (+): 
El operador de suma se utiliza para sumar dos valores. Por ejemplo:
```c#
int resultado = 5 + 3; // resultado será igual a 8
```

## Resta (-):
El operador de resta se utiliza para restar un valor de otro. Por ejemplo:
```c#
int resultado = 10 - 4; // resultado será igual a 6
```

## Multiplicación (*): 
El operador de multiplicación se utiliza para multiplicar dos valores. Por ejemplo:
```c#
int resultado = 3 * 4; // resultado será igual a 12
```

## División (/): 
El operador de división se utiliza para dividir un valor entre otro. Por ejemplo:
```c#
int resultado = 10 / 2; // resultado será igual a 5
```

## Resto
Residuo

## Incremento (++): 
El operador de incremento se utiliza para aumentar en uno el valor de una variable. Puede usarse tanto como prefijo (++i) como sufijo (i++). Por ejemplo:
```c#
int i = 5;
i++; // el valor de i será 6
```

## Decremento (--): 
El operador de decremento se utiliza para disminuir en uno el valor de una variable. Puede usarse tanto como prefijo (--i) como sufijo (i--). Por ejemplo:
```c#
int i = 5;
i--; // el valor de i será 4
```
## Característicaas de los tipos de punto flotante
De los tipos con punto flotante el mas exacto es el 'decimal'.


## Literales reales
El tipo de litera'l real viene determinado por su **sufijo**:
* d o D = `double`
* f o F = `float`
* m o M = `decimal`
```c#
double d = 3D;
d = 4d;
d = 3.964_001;

float f = 3_000.5f;
f = 5.4f;

decimal myMoney = 3_00.5m;
myMoney = 400.75M;

```

## Unarios
Un operando para funcionar

## Binarios
Dos operandos para funcionar

```C#
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");

// Suma
int num1 = 8;
double num2 = 4.5;
// Guardar el resultado en una variable
double resultado;

resultado = num1 + num2;
Console.WriteLine(resultado);

// Sumando una variable y un dato puesto explicitamente
double resultado_2 = num1 + 22;
Console.WriteLine(resultado_2);

// Sumando cadenas
string saludo = "Hola";
string nombre = "Luis";

// concatenar
string cadena_texto = saludo + " " + nombre;
Console.WriteLine(cadena_texto);

// Resta : "Rest"
double resta1 = 345 - 200;
Console.WriteLine(resta1);

// Multiplicacion
Console.WriteLine(2 * 2);
```
