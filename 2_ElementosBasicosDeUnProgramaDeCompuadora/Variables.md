# Variables
Las variables son espacios o ubicaciones en la memoria que se reservan para almacenar información de muchos tipos. Se llaman variables porque cvarian sus valores en un momento dado.
El valor de la información no simpre va a ser el mismo.
Las variables se declaran, para lo cual necestamos conocer su tipo y el nombre o etiquetta con la que la vamos a identificar y difernciarla claro de otra variable.


## Nombres de identificador
Un identificador es el nombre que se le asigna a un tipo de dato.

### Reglas para el uso de identificadores
1. Los identifficadores deben de empezar con su nombre con una letra o un guion bajo.
2. Los identificadores pueden contener numeros pero no pueden iniciar con ellos.
3. Los identificadores no pueden llevar signos.
4. Los identificadores no pueden llevar signos ni caracteres especiales a excepcion del guion bajo.
5. Los identificadores no pueden llevar espacios.

## Notacion Pascal
Se usa practicamente para todos los identificadores de nombres que vayamo viendo en c#

## camelCase
Para las variables utilizaremos Camel Case

Ejemplos de variables:
* Pascal --> SumaDosNumeros
* camelCase --> sumaDosNumeros


# Tipos de variables en C#
Las varables locales son las que estan declaradas o escritas dentro del bloque de codigo de los metodos.
Tipos de valor y tipos de referencia.

# Declaracion de una variable

```c#
// Declaracion de una variable

// Primera forma de declarar variables
int numeroLiros;
int librosNinos;
int librosMatematicas;

// Segunda Forma de declara variables, colocamos todas las variables de un mismo tipo en una linea

int numeroMaestros, numeroAlumnos, numeroPadresFamilia; // Declaramos tres variables

double promedioFinal;
```

# Inicializar una variable
Una vez declarada la variable debemos darle un valor, no simepre es necesario darle un valor desde un inicio, por ejemplo en el caso de que el usuario le asigne un valor por el teclado.

A la accion de darle un valor inicial a la variable se le conoce como inicializarla.
Cuando inicializamos un variable le estamos dando un valor por primera vez.

**Apuntes de variables**
```c#

// Declaracion de una variable

internal class Program
{
    private static void Main(string[] args)
    {
        // Primera forma de declarar variables
        int numeroLibros;
        int librosNinos;
        int librosMatematicas;

        // Segunda Forma de declara variables, colocamos todas las variables de un mismo tipo en una linea

        /* [Bloque de comentarios]
         * Declaro tres variables de tipo entero (int)
         * numeroMaestros, numeroAlumnos, numeroPadresFamilia
         */
        int numeroMaestros, numeroAlumnos, numeroPadresFamilia; // Declaramos tres variables

        double promedioFinal;

        // Inicializamos la vaiable
        numeroLibros = 500;
        // Inicializar desde el inicio, declaramos e inicializamos
        double promedioFinal = 9.8;

        char salon;
        salon = 'A'; // Solo se puede ingresar un valor con 'char', usa comillas simples

        string saludo = "Hi, School";

        bool xValue = false;

        decimal promedioExamenes = 8.5m; // No olvidar poner la 'M' al final para un tipo decimal.

        float promedioExamanesSemestrales = 8.5F; // usar la 'F' al final del 'float'
    }
}
```
