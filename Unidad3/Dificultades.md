## **⚠️Principales dificultades en la aplicación de los contenidos⚠️**

## **1. ✅Tamaño fijo y desperdicio de memoria✅**

Cuando creas un arreglo, tienes que decidir su tamaño desde el inicio.
Si pones un tamaño grande por si a caso y luego no usas todas las posiciones, se desperdicia memoria.
Pero si pones un tamaño pequeño y luego necesitas guardar más datos, no puedes ampliarlo, lo que obliga a crear otro arreglo y copiar los datos, haciendo el programa más complicado.

## **2. ⚙️Dificultad para insertar o eliminar datos⚙️**

En los arreglos, los elementos se guardan en posiciones continuas.
Si quieres insertar un nuevo dato en medio del arreglo o eliminar uno existente, tienes que mover los demás elementos manualmente para que no queden espacios vacíos.
Esto hace que el proceso sea lento y propenso a errores, especialmente cuando el arreglo tiene muchos datos.

## **3. 🔗Puede ser difícil de organizar al inicio🔗**

Aplicar modularidad significa dividir el programa en varias partes ya sea módulos o funciones.
Al comienzo, cuesta decidir qué va en cada módulo y cómo se van a comunicar entre sí.
Si no se planifica bien, el programa puede terminar con muchos módulos mal distribuidos y eso confunde más en lugar de ayudar.

## **4. 🗂️Dependencia entre módulos mal manejada🗂️**

Si los módulos no están bien separados, un cambio pequeño en uno puede afectar a otros.
Esto pasa cuando los módulos dependen demasiado entre sí y no están bien definidos.
En esos casos, la modularidad pierde su ventaja y el código se vuelve difícil de mantener y corregir.
