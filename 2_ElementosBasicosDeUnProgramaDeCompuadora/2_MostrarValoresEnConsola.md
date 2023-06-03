Para poder ver en colsola el contenido de las variables vamos a utilizar `Console.WrieLine`.

Para combinar cadenas de texto con el contenido de variables vamos a utilizar `{}`, acompañados de el indice de la variable (ver ejemplo en el siguiente codigo c#).
```c#
// Declaramos las variables e inicializamos
string saludo = "Hola";
char caracter = 'A';
double i = 8.9;

int numero1 = 78;


// Mostramos en consola las vairables
Console.WriteLine(saludo); // Muestra "Hola"
Console.WriteLine(caracter); // A
Console.WriteLine(i); // 8.9
Console.WriteLine(numero1); //78

// Cadena de formato y lista de variables
/* La cadena de formato nos permite colocar un menssaje para mostrar e indicar cual es la variable que vamos a usar.
 */

double precioCamisa = 399;
string colorCamisa = "azul";
Console.Write("El precio de la camisa es: {0} y su color es: {1}",precioCamisa, colorCamisa); // El precio de la camisa es: 399 y su color es: azul
```
