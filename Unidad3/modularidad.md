# **Modularidad**

La modularidad es un principio de diseño que consiste en dividir un sistema complejo en partes más pequeñas llamadas módulos, donde cada uno cumple una función específica y tiene una interfaz bien definida. Estos módulos pueden funcionar de forma casi independiente, pero se comunican entre sí para que el sistema completo opere correctamente. Gracias a esto, los sistemas modulares son más fáciles de entender, organizar y modificar, ya que no es necesario analizar todo el sistema al mismo tiempo para hacer cambios[12].

En el área de la ingeniería de software, la modularidad permite estructurar los programas en componentes separados, lo que facilita el desarrollo, las pruebas y el mantenimiento. Al trabajar con módulos, los errores se pueden localizar y corregir con mayor facilidad, y diferentes personas pueden trabajar en distintas partes del sistema sin interferirse. Además, la modularidad favorece la reutilización de código y el crecimiento del sistema, ya que se pueden agregar nuevas funciones modificando solo los módulos necesarios[13], [14].

Por otro lado, en el diseño de productos y sistemas físicos, la modularidad se usa para crear estructuras formadas por partes intercambiables o reemplazables. Este enfoque ayuda a reducir costos, simplificar reparaciones y adaptar los productos a nuevas necesidades sin rediseñarlos por completo. En general, la modularidad hace que los sistemas sean más flexibles, escalables y eficientes, por lo que es un concepto clave en distintas áreas de la ingeniería y el diseño[15].

# **Ejemplos de Modularidad**

## **Paso de parámetro por valor**

Cuando pasas un argumento por valor a una función en C, lo que realmente hace el lenguaje es crear una copia del valor y usar esa copia dentro de la función. Eso significa que los cambios que se hagan dentro de la función no afectan al valor original que está en el main, porque la función solo ve una copia del dato[16].

<img width="725" height="422" alt="modularida 1" src="https://github.com/user-attachments/assets/8519e9b2-8495-45be-8de5-91db0bfc3afc" />

## **Paso de parámetro por referencia**

En C no existe “paso por referencia” como tal en la sintaxis del lenguaje, pero puedes simularlo usando punteros: en lugar de enviar el valor, envías la dirección de memoria de una variable. De este modo, la función puede acceder y modificar el valor original usando esa dirección, lo que resulta en una forma práctica de pasar parámetros por referencia[17].

<img width="733" height="405" alt="Modularidad 2" src="https://github.com/user-attachments/assets/d8aa1504-08b6-4198-8672-bac2b20ecf12" />
