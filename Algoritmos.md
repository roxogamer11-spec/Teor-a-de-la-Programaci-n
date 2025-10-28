
🧩 **Algoritmos**

Un algoritmo es una serie de pasos ordenados que permiten resolver un problema o alcanzar un objetivo de manera lógica y eficiente. En la vida cotidiana usamos algoritmos constantemente sin darnos cuenta; por ejemplo, al seguir una receta de cocina, organizar nuestras actividades diarias, preparar una maleta para un viaje o dar indicaciones para llegar a un lugar. Estos pasos nos ayudan a asegurarnos de que cada acción se realiza en el orden correcto para obtener el resultado esperado. En programación, los algoritmos son fundamentales porque constituyen la base lógica de todo programa: antes de escribir cualquier línea de código, es necesario planificar y estructurar cómo se resolverá el problema, definiendo claramente cada paso y anticipando posibles dificultades que puedan surgir durante la ejecución.

Un buen algoritmo debe ser claro, preciso y tener un inicio y un final definidos, evitando ambigüedades que puedan generar errores o resultados inesperados. Además, un algoritmo eficiente no solo resuelve el problema correctamente, sino que también optimiza recursos y tiempo, facilita la comprensión del programa por parte de otros desarrolladores y sirve como guía para la implementación en cualquier lenguaje de programación. La claridad y la estructuración adecuada del algoritmo permiten que otras personas puedan entenderlo y reproducirlo, algo fundamental en proyectos colaborativos y en entornos educativos.

Comprender y practicar la creación de algoritmos fortalece el pensamiento lógico, la capacidad de análisis y la resolución de problemas, habilidades esenciales tanto en la programación como en la vida cotidiana. Además, desarrollar buenos algoritmos fomenta la disciplina, la organización y la anticipación de posibles errores, lo que contribuye a diseñar soluciones más eficientes y efectivas. A medida que se adquiere experiencia, se puede aplicar la lógica algorítmica a problemas más complejos, combinando secuencias, condicionales y bucles, y creando programas que no solo funcionen correctamente, sino que también sean óptimos, claros y fáciles de mantener.[1]

🔄 **Diagrama de flujo**

El diagrama de flujo es una representación gráfica de un algoritmo que permite visualizar de manera clara y ordenada la secuencia lógica de las operaciones que se deben realizar. Esta herramienta utiliza diferentes símbolos que representan elementos específicos del proceso: los óvalos indican el inicio y el fin, los rectángulos representan acciones o procesos, los rombos señalan decisiones o condiciones, y los paralelogramos se utilizan para entradas y salidas de datos. La ventaja de esta representación visual es que facilita la comprensión del algoritmo, ya que permite identificar cada paso, su relación con los demás y el flujo de información, haciendo evidente dónde se toman decisiones y cómo afectan al resultado final.

Además, los diagramas de flujo son fundamentales para detectar errores, optimizar procesos y planificar programas complejos antes de escribir código. Al representar un algoritmo gráficamente, es posible anticipar problemas, reorganizar pasos y simplificar procedimientos, lo que ahorra tiempo y reduce errores durante la programación. Por ejemplo, en un proyecto de software, un diagrama de flujo bien elaborado puede ayudar a identificar caminos lógicos redundantes o pasos innecesarios, mejorando la eficiencia del programa. Asimismo, facilita la comunicación entre desarrolladores o estudiantes, ya que incluso quienes no tienen experiencia en programación pueden entender cómo funciona un proceso paso a paso.

El uso constante de diagramas de flujo refuerza el pensamiento lógico y estructurado, desarrollando habilidades para organizar ideas, resolver problemas de manera sistemática y diseñar algoritmos claros, eficientes y fáciles de implementar. En entornos educativos y profesionales, dominar la creación y lectura de diagramas de flujo constituye una competencia esencial para la elaboración de programas efectivos, el trabajo colaborativo y la comprensión profunda de los procesos involucrados. Su aprendizaje no solo fortalece la capacidad de planificación y análisis, sino que también sienta las bases para la transición hacia estructuras más complejas, como bucles, condicionales y programación modular, preparando al estudiante o profesional para enfrentar desafíos de programación cada vez más avanzados.[2]

💬 **Pseudocódigo**

El pseudocódigo es una herramienta que sirve como puente entre el lenguaje natural y los lenguajes de programación, permitiendo describir algoritmos de manera clara y estructurada sin necesidad de seguir la sintaxis estricta de un lenguaje de programación. Se utiliza para expresar la lógica de un programa de forma comprensible, combinando expresiones del lenguaje cotidiano con una organización lógica similar a la del código real. Esto facilita que cualquier persona, incluso sin conocimientos previos de programación, pueda entender los pasos necesarios para resolver un problema o completar una tarea específica. Su uso es especialmente útil durante la fase de planificación de un algoritmo, ya que permite enfocarse en la lógica antes de preocuparse por detalles técnicos de codificación.

El pseudocódigo también facilita la traducción del pensamiento lógico a estructuras de control reales, como bucles, condicionales y secuencias de instrucciones. Al representar un algoritmo de esta manera, se pueden identificar errores, redundancias o pasos innecesarios antes de implementar el código en un lenguaje de programación específico. Esto ayuda a optimizar el proceso de desarrollo, reduce la posibilidad de fallos y hace más eficiente la escritura del programa final. Además, el pseudocódigo permite estandarizar y comunicar algoritmos entre diferentes personas o equipos, asegurando que todos comprendan la lógica detrás de un programa sin depender de un lenguaje de programación particular.

Por último, el uso del pseudocódigo fortalece habilidades esenciales como el pensamiento lógico, la organización de ideas y la resolución de problemas, ya que obliga a descomponer un problema complejo en pasos simples y ordenados. Es una herramienta educativa fundamental para estudiantes de programación, ya que prepara el camino para escribir código real de manera más estructurada y eficiente. Además, al ser fácilmente entendible, permite revisar, mejorar y colaborar en algoritmos antes de su implementación, consolidando una base sólida para la programación profesional y para la creación de soluciones eficientes en cualquier contexto.[3]



**Ejemplo**


📥#include <stdio.h>📥

📥int main() {📥
    
    📥double Certamen1, Certamen2, Certamen3, NotaLaboratorio, Final;📥
    
    📥printf("Ingrese el Certamen 1\n");📥
    
    scanf("%i",&Certamen1);
    
    printf("Ingrese el Certamen 2\n");
    
    scanf("%i",&Certamen2);
    
    printf("Ingrese la nota del Laboratorio\n");
    
    scanf("%i",&Certamen3);
    
    Final <- 60;
    
    Certamen3 = (3 * (60 - (NotaLaboratorio * 0.3))) / 0.7 - ( Certamen1 + Certamen2);
    
    printf("Para aprobar con una nota final de 60, necesitas obtener; %i\n", Certamen3);
    
    📥return 0;📥

📥}



┌────────────────────────────┐
│        INICIO              │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ Leer Certamen1             │
│ Leer Certamen2             │
│ Leer NotaLaboratorio       │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ Final ← 60                 │
│ Certamen3 ← (3*(60-(NotaLaboratorio*0.3)))/0.7 - (Certamen1+Certamen2) │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│ Mostrar “Para aprobar con  │
│ 60 necesitas: Certamen3”   │
└────────────┬───────────────┘
             │
             ▼
┌────────────────────────────┐
│          FIN               │
└────────────────────────────┘





