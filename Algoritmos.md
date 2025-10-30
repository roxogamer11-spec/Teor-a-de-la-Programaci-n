
# 🧩 **Algoritmos**

Un algoritmo es una serie de pasos ordenados que permiten resolver un problema o alcanzar un objetivo de manera lógica y eficiente. En la vida cotidiana usamos algoritmos constantemente sin darnos cuenta; por ejemplo, al seguir una receta de cocina, organizar nuestras actividades diarias, preparar una maleta para un viaje o dar indicaciones para llegar a un lugar. Estos pasos nos ayudan a asegurarnos de que cada acción se realiza en el orden correcto para obtener el resultado esperado. En programación, los algoritmos son fundamentales porque constituyen la base lógica de todo programa: antes de escribir cualquier línea de código, es necesario planificar y estructurar cómo se resolverá el problema, definiendo claramente cada paso y anticipando posibles dificultades que puedan surgir durante la ejecución.[1]

Un algoritmo esta compuesto por tres partes las cuales son:

# 🟢**Las Entradas**🟢

Son todos los datos o información que el usuario proporciona para que el algoritmo pueda realizar sus operaciones o procesos, es decir, las entradas representan los valores iniciales necesarios para que el algoritmo funcione correctamente y produzca un resultado. Sin las entradas adecuadas, el algoritmo no podría ejecutar sus cálculos ni generar salidas válidas.
Usualmente, para deteminar las entradas, se suele tomar en cuanta la siguiente pregunta: ¿Qué datos necesito que me de otra persona para poder obtener la solución del problema?.

# ⚙️**Los Procesos**⚙️

Son el conjunto de operaciones, cálculos o pasos que el algoritmo debe realizar para transformar las entradas en resultados. En esta etapa se lleva a cabo la transformacion de las entradas , aplicando fórmulas, comparaciones o instrucciones que permiten resolver el problema planteado. En otras palabras, los procesos constituyen el núcleo del algoritmo, donde se desarrolla el razonamiento que conduce a la solución.
Usualmente, para deteminar los procesos, se suele tomar en cuanta la siguiente pregunta: ¿Cuáles son los pasos para llegar al resultado partiendo de los datos?

# 💡**Las Salidas**💡

Son los resultados obtenidos después de ejecutar todos los procesos del algoritmo. Representan la información final que el programa muestra al usuario tras haber realizado los cálculos, operaciones o transformaciones necesarias. En otras palabras, las salidas son la respuesta o solución al problema planteado, generada a partir de las entradas procesadas por el algoritmo.
Usualmente, para deteminar las salidas, se suele tomar en cuanta la siguiente pregunta: ¿Cuál es el resultado que se desea obtener?

[ **🔑🔑Algoritmos en PSeInt**🔑🔑](PS.md)

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

# **Lenguaje compilado**

Un programa escrito en un lenguaje compilado necesita ser traducido mediante un software especial llamado compilador. Este compilador convierte el código fuente (escrito por el programador) en un programa objeto, que contiene instrucciones entendibles por la computadora. Posteriormente, este programa objeto se usa para generar un archivo ejecutable, el cual puede ejecutarse directamente sin requerir más traducciones. De esta forma, el compilador permite transformar el código del programador en un programa funcional que la máquina puede comprender y ejecutar.

# **Ejemplo de un Lenguaje compilado**

<img width="451" height="140" alt="copi" src="https://github.com/user-attachments/assets/a17af2c5-0b6b-41e0-a245-54eb85f6d893" />

Como se puede ver en la imagen, el programa usa el comando gcc para compilar el código. Este comando le indica a la computadora que debe leer el código fuente escrito por el programador y traducirlo a un lenguaje que la máquina pueda entender. Durante este proceso, el compilador revisa que no existan errores en el código, y si todo está correcto, crea un archivo ejecutable que luego se puede abrir para ver el resultado del programa en funcionamiento. En pocas palabras, gcc es la herramienta que convierte el código que escribimos en C en un programa que la computadora puede ejecutar.

# 🔄 **Diagrama de flujo**

El diagrama de flujo es una representación gráfica de un algoritmo que permite visualizar de manera clara y ordenada la secuencia lógica de las operaciones que se deben realizar. Esta herramienta utiliza diferentes símbolos que representan elementos específicos del proceso: los óvalos indican el inicio y el fin, los rectángulos representan acciones o procesos, los rombos señalan decisiones o condiciones, y los paralelogramos se utilizan para entradas y salidas de datos. La ventaja de esta representación visual es que facilita la comprensión del algoritmo, ya que permite identificar cada paso, su relación con los demás y el flujo de información, haciendo evidente dónde se toman decisiones y cómo afectan al resultado final.[2]

# ✨**Ejemplo Práctico de un Diagrama de Flujo en PSeInt**✨

<img width="519" height="515" alt="Captura de pantalla 2025-10-29 090441" src="https://github.com/user-attachments/assets/4732cbc3-964f-4fa5-9d69-9a809e584b49" />


# 💬 **Pseudocódigo**

El pseudocódigo es una herramienta que sirve como puente entre el lenguaje natural y los lenguajes de programación, permitiendo describir algoritmos de manera clara y estructurada sin necesidad de seguir la sintaxis estricta de un lenguaje de programación. Se utiliza para expresar la lógica de un programa de forma comprensible, combinando expresiones del lenguaje cotidiano con una organización lógica similar a la del código real. Esto facilita que cualquier persona, incluso sin conocimientos previos de programación, pueda entender los pasos necesarios para resolver un problema o completar una tarea específica. Su uso es especialmente útil durante la fase de planificación de un algoritmo, ya que permite enfocarse en la lógica antes de preocuparse por detalles técnicos de codificación.

Por último, el uso del pseudocódigo fortalece habilidades esenciales como el pensamiento lógico, la organización de ideas y la resolución de problemas, ya que obliga a descomponer un problema complejo en pasos simples y ordenados. Es una herramienta educativa fundamental para estudiantes de programación, ya que prepara el camino para escribir código real de manera más estructurada y eficiente. Además, al ser fácilmente entendible, permite revisar, mejorar y colaborar en algoritmos antes de su implementación, consolidando una base sólida para la programación profesional y para la creación de soluciones eficientes en cualquier contexto.[3]


[ **🔑🔑Tipos de Datos**🔑🔑](Datos.md)

[ **🔑🔑Variables y Constantes**🔑🔑](Vari.md)

[ **🔑🔑Expreciones y Expreciones por Computadora**🔑🔑](Expre.md)

[ **🔑🔑Pruebas de Escritorio**🔑🔑](Escri.md)






