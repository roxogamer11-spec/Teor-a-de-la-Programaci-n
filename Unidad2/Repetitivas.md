# **for**

El ciclo for se utiliza cuando se conoce previamente el número exacto de repeticiones, este incluye en una sola línea el valor inicial, la condición que controla cuántas veces se ejecuta el ciclo y la actualización del contador. Es ideal para recorrer listas, realizar iteraciones controladas o ejecutar tareas repetitivas con un rango definido, es decir permite un control más organizado cuando se trabaja con contadores [9].

A continuacion se muestra como ejemplo, un programa el cual solicita al usuario que ingrese un número entre 1 y 10 y luego utiliza un ciclo for para generar y mostrar la tabla de multiplicar correspondiente a ese número. Después de leer el valor ingresado, el programa inicia un contador j que va desde 1 hasta 10, y en cada repetición calcula y muestra el resultado de multiplicar el número dado ( i ) por el valor actual del contador ( j ). Así, se imprimen todas las multiplicaciones desde i x 1 hasta i x 10. En resumen, el ejercicio produce la tabla de multiplicar del número que el usuario elige usando un ciclo repetitivo.

<img width="605" height="658" alt="for" src="https://github.com/user-attachments/assets/687e5c42-46bc-439e-afc5-9feff2f0f544" />

## **Ejemplo en Diagrama de Flujo**

<img width="687" height="506" alt="for 2" src="https://github.com/user-attachments/assets/4cee8b61-7de5-487c-b6d2-870c795b597c" />

# **while**

El ciclo while ejecuta las instrucciones mientras la condición sea verdadera. Se recomienda usarlo cuando no se sabe con exactitud cuántas veces debe repetirse la acción, ya que depende del cumplimiento de una condición externa o del cambio de una variable dentro del mismo ciclo. Como evalúa la condición antes de entrar, es posible que el bloque nunca se ejecute si la condición es falsa desde el inicio[10].

A continuacion se muestra un programa tomado como ejemplo, el cual solicita al usuario el número de la tabla de multiplicar que desea generar, siempre dentro del rango del 1 al 10. Después de leer ese valor, muestra un encabezado indicando la tabla seleccionada y utiliza un ciclo while para repetir las multiplicaciones desde 1 hasta 10. En cada iteración imprime la operación correspondiente, mostrando el número ingresado multiplicado por el contador i, el cual se incrementa en 1 en cada vuelta del ciclo. El proceso continúa mientras i sea menor o igual a 10, generando así toda la tabla de multiplicar seleccionada por el usuario.

<img width="599" height="660" alt="while" src="https://github.com/user-attachments/assets/d55b128b-800e-4b20-aa4c-8111068513ee" />

## **Ejemplo en Diagrama de Flujo**

<img width="487" height="471" alt="while 2" src="https://github.com/user-attachments/assets/d59becd5-4c57-4094-8369-f8154e7a97b2" />

# **Do - while**

El ciclo do - while garantiza que el bloque de instrucciones se ejecute al menos una vez, porque la verificación de la condición se hace al final del ciclo. Es útil en situaciones donde necesitas que el programa pregunte o genere algo antes de verificar si debe continuar, como menús interactivos, lectura de datos o procesos que deben ejecutarse mínimo una vez antes de evaluar una condición[11].

A continuacion se muestra un programa que solicita al usuario un número y luego utiliza un bucle do-while para generar su tabla de multiplicar del 1 al 10. El contador inicia en 1 y, dentro del bloque do, se imprime la operación correspondiente. Después, el contador aumenta en 1 y el ciclo continúa mientras el valor sea menor o igual a 10. El uso de do-while asegura que la tabla se imprima al menos una vez, incluso si el valor inicial del contador cambiara.

<img width="610" height="662" alt="do" src="https://github.com/user-attachments/assets/d597e1ec-b293-458c-81e7-1c91f008e9c4" />

## **Ejemplo en Diagrama de Flujo**

<img width="569" height="500" alt="do 2" src="https://github.com/user-attachments/assets/9ce0c985-13ca-46b4-b1ca-84ef9facb401" />
