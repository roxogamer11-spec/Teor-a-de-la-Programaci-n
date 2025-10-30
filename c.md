# **Lenguaje de programacion de alto nivel**

# **Codificación**

Realizar la conversión de un algoritmo a un lenguaje de programación no consiste únicamente en reemplazar las palabras reservadas del pseudocódigo en español por sus equivalentes en inglés. También es necesario agregar elementos que el pseudocódigo suele omitir, como la declaración de variables, constantes y librerías necesarias para que el programa funcione correctamente. En esta etapa, el algoritmo se transforma en un código completo y entendible por el compilador, listo para ser ejecutado en el lenguaje elegido.

# ** Librerias y Bibliotecas**

Son archivos que se encuentran en la parte inicial (cabecera) de los programas y contienen código ya escrito que permite realizar operaciones y cálculos comunes sin tener que programarlos desde cero. Cada compilador incluye sus propias librerías, y el programador debe incluir o “llamar” aquellas que necesite para que su programa funcione correctamente.

# ** Ejemplo de una Biblioteca**

#include <librería.h>

# **Lenguaje de programación C**

El lenguaje de programación C fue creado por Dennis Ritchie en el año de 1970, como parte del desarrollo del sistema operativo UNIX, este lenguaje nació con el objetivo de ser un lenguaje eficiente que permitiera acceder directamente al hardware y al sistema operativo, combinando características de bajo nivel y alto nivel, lo que lo convierte en un lenguaje de nivel medio. El lenguaje C es un potente lenguaje de propósito general destacado por su velocidad, eficiencia y control del hardware. Es la base de muchos lenguajes modernos como C++ y Java, y se utiliza en sistemas operativos, motores de juegos y sistemas embebidos.

# **Como ingresar los datos en c**

En el lenguaje C, el ingreso de datos se realiza principalmente a través del teclado, utilizando la función scanf(). Esta función permite leer valores introducidos por el usuario y almacenarlos en variables para que el programa pueda usarlos más adelante, antes de leer los datos, se suele usar la función printf() para mostrar un mensaje en pantalla, indicando al usuario qué tipo de información debe ingresar.

# **Ejemplo**

printf("Ingrese un número: ");

scanf("%d", &numero);

# **El símbolo "&" y las Mascaras**

<img width="442" height="245" alt="mas 1" src="https://github.com/user-attachments/assets/b1b37fe0-d211-4844-98ef-ce3db02423c8" />


Este simbolo se utiliza en el lenguaje C para indicar la dirección de memoria de una variable, es decir, el lugar donde se almacenará el dato que el usuario ingrese. Cuando se usa con la función scanf(), este símbolo permite que el valor introducido por el usuario se guarde directamente dentro de la variable correspondiente, en lugar de solo copiarlo temporalmente. De esta forma, scanf() sabe exactamente dónde colocar el dato leído en la memoria del programa.

# ✨**Ejemplo Práctico de un Algoritmo en C**✨

<img width="380" height="250" alt="Captura de pantalla 2025-10-29 092339" src="https://github.com/user-attachments/assets/f3638ed8-3b5a-4e5f-9288-9f024f4a3be5" />

Esta imagen muestra un ejemplo en el lenguaje C, el cual suma dos valores ingresados por el usuario al igual que en PSeInt. En primer lugar, se declaran tres variables de tipo double llamadas a, b y c, las cuales permiten almacenar los valores ingresados por el usuario. A continuación, el programa solicita al usuario que introduzca el primer y segundo. Luego, se realiza la operación correspondiente sumando las variables a y b, y el resultado se guarda en la variable c. Finalmente, mediante la función printf(), el programa muestra en pantalla el mensaje con el resultado obtenido.
