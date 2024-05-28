## Apuntes de Fundamentos de la Programación Orientado a Objetos
###### _No olvides darle una estrellita a este repositorio :D  -_ <img src="https://i.ibb.co/0nX0bNR/Screenshot-2024-05-07-164050.png" alt="Screenshot-2024-05-07-164050" border="0" height="30em" align="center">
###### Hay un archivo llamado **preguntas.md** en donde estan las posibles preguntas teoricas.
<img src="https://i.ibb.co/ryRMhP0/fpoo.png" alt="fpoo" border="0" height="370em"><br> 
##
# 🟢 SEMANA 01
### **😵‍💫 PROBLEMA Y SOLUCIÓN**
<br>

| |
|---|
| **_"La programación surge como respuesta a la necesidad de resolver problemas mediante la ejecución de instrucciones por un ordenador"_**|

<br>

### **📚 CONCEPTO DE PROBLEMA**

Un problema en **términos generales** se puede conceptualizar de las siguientes maneras: 
- Es un asunto o cuestión que se debe solucionar o aclarar.
- Una contradicción o un conflicto entre lo que es y lo que debe ser.
- Una dificultad o un inconveniente para la consecución de un fin.
- Un disgusto, una molestia o una preocupación.
<br>

El  concepto de problema derivado de la Ingeniería en su libro Introducción a la ingeniería (1998) el autor **Krick afirma** que: <br>
| |
|---|
|**_“Un problema proviene del deseo de lograr la transformación de un estado en otro”_**| 
<br>

Ejemplo:
<br>
Si una persona está enferma **(Estado A)** , nace la necesidad o deseo de mejorar la salud; es decir
pasar a que esa persona esté saludable **(Estado B)**, por medio de un tratamiento, operación o
cualquier otra acción que produzca el cambio de estado. 
<br>
ejemplo 2:
<br>
Se necesita enseñar a niños a cruzar la calle (**Estado A:** niños no saben cruzar la calle) de una
manera entretenida y educativa (**Estado B:** los niños aprendieron a cruzar la calle).

### **🧩 PARTES DE UN PROBLEMA**
Todo problema está compuesto, conceptualmente, por tres partes o aspectos:
1. **Un estado inicial**, **“A”** inferior, que se manifiesta por medio de síntomas, efectos o
consecuencias producto de una carencia, necesidad, deseo o expectativa que se desea
o requiere satisfacer. Esto es lo que el común de la gente denomina erradamente
problema, confundiendo los síntomas con las causas y con el verdadero problema.
Desde el punto de vista de quien tiene la necesidad o el deseo, esta fase se podría
denominar acertadamente **“situación problemática”.**<br>

2. Un **estado final**, superior **“B”**, el cual corresponde a la solución del problema, a la
satisfacción de la necesidad o al valor agregado esperado. Alcanzar esta meta es el
objetivo principal de la disciplina de la ingeniería en sus diferentes ramas, es decir, es
el ”que hacer” del ingeniero. El valor agregado de todos los proyectos y diseños de
ingeniería se mide por el grado y la calidad alcanzados del estado *”B”*.<br>

3. El proyecto, etapa que corresponde a las **estrategias** empleadas para darle solución al
problema o para satisfacer la necesidad o el deseo planteado en la primera etapa. Es en
esta fase del problema donde el profesional aplica los conocimientos, habilidades y
destrezas adquiridas durante sus estudios profesionales, es decir, sus competencias en
el campo o problemática respectiva.<br>

ejemplificación de los estados A y B de un problema:

| ESTADO A | ESTRATEGIA | ESTADO B |
|-----------|-----------|-----------|
| Estudiante de Tec. Universitaria en Desarrollo Integral de Videojuegos  |⟹| Técnico/a Universitario/a en Diseño Integral de Videojuegos  |
| Árbol  |⟹| Papel |
| Construcción Proyectada |⟹| Edificio terminado |
| Idea de videojuego  |⟹| Videojuego construido  |

### **⬛ Problema y Solución desde una visión de “Caja Negra”** 
<br>

![image](https://github.com/AlexUnju/apuntes_fpoo/assets/142057928/2c615719-7ba4-4fa4-97e9-4ca3c173e74e)

##  VIDEO YOUTUBE PROBLEMA Y SOLUCION <img src="https://i.ibb.co/0Y8QBHD/yt.png" alt="yt" border="0" height="20"> <br>

[![Texto alternativo](https://img.youtube.com/vi/ickYKg0MyCk/maxresdefault.jpg)](https://www.youtube.com/watch?v=ickYKg0MyCk)

## **<img src="https://cdn-icons-png.flaticon.com/512/1448/1448776.png" height="25" align="left">PROGRAMACIÓN**

Cuando la **estrategia** adoptada para obtener el estado deseado implica que los procesos sean
realizados por un ordenador; o dicho de otra manera cuando los sistemas utilizan procesos que
son llevados a cabo por un ordenador, entonces implícitamente estos **sistemas recurrieron a la
programación**.

### **📚 CONCEPTO DE PROGRAMACIÓN**

El concepto de programación abarca diferentes perspectivas en Ingeniería del Software. Desde **la codificación y documentación de programas en lenguajes específicos** hasta **el arte de traducir deseos humanos en instrucciones comprensibles para las computadoras**. Es un proceso creativo que implica **_limpiar, codificar, trazar y proteger el código fuente_**. En esta materia, se destaca que **la programación es tanto una disciplina como un arte** para crear software, donde un programador requiere habilidades esenciales para garantizar **la calidad del producto final, medida en términos de escalabilidad, reutilización y facilidad de mantenimiento.**

![image](https://github.com/AlexUnju/apuntes_fpoo/assets/142057928/64215b0e-66ed-4453-b5a0-9dbb16c04880)

### **📕 CONCEPTOS DERIVADOS DE LA PROGRAMACIÓN**

**_Un programa de software es un conjunto de sentencias o instrucciones (algoritmos) escritos en
un lenguaje de programación._**  <br>

Los programas forman parte de un conjunto más grande
denominado **producto software**, el cual incluye los programas, **la documentación de los
programas, la documentación de análisis y diseño de los programas, el manual de usuario, etc.**

En el desarrollo de un videojuego, el producto software incluye el código fuente, el ejecutable, los instaladores, el manual, el documento de diseño (GDD), listas de assets y sonidos, concept art y la historia del juego.

En términos generales, un lenguaje de programación es una herramienta que permite desarrollar programas para computadoras. Está compuesto por símbolos y reglas de sintaxis y semántica que definen su estructura y significado. El programador debe entender estas características para escribir algoritmos. Su función principal es proporcionar un entorno para que los programadores creen programas que faciliten la comunicación entre el usuario y la máquina.

Son muchos los tipos de lenguaje con los que un programador puede trabajar, pero nosotros
nos centraremos en dos: **Los lenguajes de bajo nivel y los lenguajes de alto nivel**.
#### ⬇️ Lenguaje de bajo nivel

El **lenguaje de bajo nivel** presenta ventajas como su sencillez, instrucciones directas y alta velocidad de ejecución. Sin embargo, está estrechamente ligado al hardware, lo que puede dificultar la estructuración de ciertos programas. Además, se requiere atención especial para evitar errores que puedan aumentar la carga de trabajo y revisión del código.
#### ⬆️ Lenguaje de alto nivel
Cuando hablamos de **lenguajes de alto nivel**, nos referimos a aquellos que se centran en las capacidades cognitivas humanas en lugar de en las capacidades de las máquinas. Estos lenguajes permiten a los programadores resolver problemas de manera sencilla y rápida, ofreciendo máxima flexibilidad y abstracción. Aunque generan un código más comprensible y válido para diversas plataformas, pueden ralentizar el procesamiento ya que la computadora necesita más tiempo para traducir las instrucciones. Además, algunos están limitados a ciertas plataformas. En general, para los productos de software que se desarrollarán, los algoritmos se escribirán en un lenguaje de alto nivel.

##  VIDEO YOUTUBE PROGRAMACIÓN <img src="https://i.ibb.co/0Y8QBHD/yt.png" alt="yt" border="0" height="20"> <br>
[![Texto alternativo](https://img.youtube.com/vi/IUTNblDwOfE/maxresdefault.jpg)](https://www.youtube.com/watch?v=IUTNblDwOfE)
 
### 📑 FASES EN RESOLUCION DE PROBLEMAS MEDIANTE ALGORITMOS

El proceso de resolución de problemas con una computadora implica escribir y ejecutar un programa. Aunque es un proceso creativo, sigue una serie de fases comunes que deben seguir la mayoría de los programadores.

### 📖 FASES EN LA RESOLUCIÓN DE PROBLEMAS CON COMPUTADORA
Las fases de resolución de un problema con computadora son:
1 - Análisis del problema.
2 - Diseño del algoritmo.
3 - Codificación.
4 - Compilación y ejecución.
5 - Verificación.
6 - Depuración.
7 - Mantenimiento.
8 - Documentación.

  **Las características principales de la resolución de problemas son:**

1. **Análisis:** Se estudia el problema considerando los requisitos especificados por el cliente o la persona encargada del programa.
2. **Diseño:** Se elabora una solución que conduzca a un algoritmo para resolver el problema.
3. **Codificación (Implementación):** La solución se traduce a la sintaxis de un lenguaje de alto nivel (como Java, C#, Processing, etc.) para crear archivos de código fuente, que luego se traducen al lenguaje de la computadora.
4. **Ejecución, Verificación y Depuración:** El programa se ejecuta, se verifica rigurosamente y se corrigen los errores ("bugs") que puedan surgir.
6. **Mantenimiento:** El programa se actualiza y modifica según las necesidades de los usuarios.
7. **Documentación:** Se documentan las diferentes fases del ciclo de vida del software, incluyendo análisis, diseño, codificación, así como manuales de usuario y de referencia, y normas para el mantenimiento.
Las dos primeras fases llevan al diseño detallado en forma de algoritmo. Durante la tercera fase (codificación), se implementa este algoritmo en código. La compilación y ejecución traducen y ejecutan el programa. En las fases de verificación y depuración, se buscan y corrigen errores. Es fundamental invertir tiempo en análisis y diseño para reducir la necesidad de depuración. Por último, se documenta el programa.

### ✍️ ALGORITMO Y METODOLOGÍA DE LA PROGRAMACIÓN

Un algoritmo es un método para resolver un problema mediante una serie de pasos precisos,
definidos y finitos. Estas últimas tres palabras, son además las características de un algoritmo:
- **Preciso:** Indica el orden de realización de cada paso.
- **Definido:** Si se sigue dos veces, obtiene el mismo resultado cada vez.
- **Finito:** Tiene fin, un determinado número de pasos.Debe producir un resultado en un tiempo finito.

Los métodos que utilizan algoritmos se llaman métodos algorítmicos, mientras que los métodos que implican juicio se denominan métodos heurísticos.
El eje central de esta metodología es el concepto de algoritmo.
![image](https://github.com/AlexUnju/apuntes_fpoo/assets/142057928/7d08362e-a0b7-4243-8c11-8627cdece737)


Se consideran todos los elementos de un problema representado como un sistema informático:

1. Los datos de entrada (la situación problemática) y los datos de salida (la solución) son esenciales para diseñar un algoritmo.

2. El diseño de un algoritmo implica una secuencia ordenada de pasos sin ambigüedades que conducen al desarrollo del proceso o estrategia. Esto incluye tanto la fase de análisis del problema como la fase de diseño del algoritmo, donde se crea un modelo del programa que aún no ha sido codificado.

3. A partir del diseño del algoritmo, se construye el programa en la fase de codificación o implementación.

4. El programa, junto con la configuración del hardware y los documentos de desarrollo, constituyen el software del sistema informático. En este paso, el sistema puede ejecutarse, verificarse y depurarse, lo que corresponde a la fase de ejecución de la resolución de problemas mediante algoritmos.


|   |
|---|
| Entonces, la idea central de la Metodología de la Programación es que para llegar a la realización de un programa es necesario el diseño previo de un algoritmo, de modo que sin algoritmo no puede existir un programa. |

Los algoritmos son independientes del lenguaje de programación y la computadora. Pueden expresarse en diferentes lenguajes y ejecutarse en diferentes máquinas manteniendo su esencia. En la ciencia de la computación, los algoritmos son más importantes que los lenguajes de programación o las computadoras. Un lenguaje de programación es solo un medio para expresar un algoritmo, y una computadora es simplemente un procesador para ejecutarlo.

### 🧠 ANÁLISIS DEL PROBLEMA

El análisis del problema comprende dos etapas:

1. **Definición:** Se establece el propósito del algoritmo y se define claramente lo que se desea resolver, junto con los objetivos de su solución.

2. **Análisis:** Se identifican las características del problema en términos de entradas y salidas, y se investigan los procesos necesarios para resolverlo. Se selecciona el proceso más adecuado si hay varias opciones disponibles, o se desarrolla uno si no existen procesos previos.

![image](https://github.com/AlexUnju/apuntes_fpoo/assets/142057928/f334e5fc-337c-497c-9817-e79a4f1811c9)

**Ejemplo:** Se solicita desarrollar una calculadora que permita sumar dos números

**Definición del Problema:** Desarrollar una calculadora que permita sumar dos números

**Análisis:**
- Datos de Entrada: Dos números, a los cuales denominaremos número A y número B
- Proceso:
-  - - ¿Quién debe realizar el proceso?: Una calculadora
-  - - Cuál es el proceso que realiza la calculadora?
              
Donde lo que se ha aplicado es una ecuación matemática que la calculadora
puede realizar. La variable dependiente suma almacena el resultado de sumar
al número A, el número B.
- - - Datos de Salida: suma

### **📏 Consideraciones previas a la representación de un algoritmo**

**Una variable** es un contenedor para almacenar información, compuesto por un identificador único y un tipo de datos que determina el rango de valores y operaciones aplicables. Los tipos de datos más comunes incluyen **Entero, Real o Flotante, Carácter, Cadena de caracteres o string, y Fecha.** 

**La nomenclatura** del identificador sigue ciertas reglas comunes, como la unicidad y claridad del nombre, evitando el inicio con números y utilizando mayúsculas para separar palabras en nombres compuestos. Se sugiere evitar nombres excesivamente largos para facilitar la legibilidad. 

Además, se establecen convenciones para nombres específicos, como **i, j, k para índices enteros**, **a, b, c para valores numéricos reales**, las variables llamadas **p y q se emplean para
apuntadores**; las variables llamadas **n y m son variables que contienen valores de tamaños de matrices.**
Los nombres de variables se escriben en minúsculas para facilitar la lectura.

### 🎨 DISEÑO DEL ALGORITMO
![image](https://github.com/AlexUnju/apuntes_fpoo/assets/142057928/7e83a87e-c4a6-466d-8c50-cc146e507da1)

#### CONCLUSIÓN

El diseño de algoritmos es crucial en la ciencia de la computación y se enfatiza en esta materia. Requiere creatividad y conocimiento técnico. Los algoritmos pueden representarse de diversas formas. Se recomienda tomarse tiempo para analizar y diseñar antes de codificar, lo que evita problemas en la implementación.

##  VIDEO FASES EN RESOLUCIÓN DE UN ALGORITMO <img src="https://i.ibb.co/0Y8QBHD/yt.png" alt="yt" border="0" height="20"><br>

[![Texto alternativo](https://i.ytimg.com/vi/zXHAjyVmYEE/hqdefault.jpg?sqp=-oaymwE2CNACELwBSFXyq4qpAygIARUAAIhCGAFwAcABBvABAfgB_gmAAtAFigIMCAAQARhLIGUoOjAP&rs=AOn4CLCF5C2YNiaAYsIp4KSbog7pP8BWnA/maxresdefault.jpg)](https://www.youtube.com/watch?v=zXHAjyVmYEE)
#
# 🔵 SEMANA 02
##
### 🧮 EXPRESIÓN ARITMÉTICA
Las expresiones son combinaciones de constantes, variables, operadores y paréntesis. En algoritmos, las expresiones algebraicas se traducen a expresiones aritméticas. Los operandos son las variables o constantes involucradas, mientras que los operadores realizan las operaciones entre ellos. El resultado de una expresión aritmética es numérico, ya sea entero o real, y el punto se usa como separador decimal . Por ejemplo, suponga que 𝑏 = 4.5


### 📚 OPERADORES ARITMÉTICOS

| Operador          | Descripción                      |
|-------------------|----------------------------------|
| +                 | Suma                             |
| -                 | Resta                            |
| *                 | Multiplicación                   |
| /                 | División                         |
| ** o ^            | Potenciación                     |
| div               | División entera                  |
| mod, %            | Módulo (resto)                   |

Ejemplo:

| Operación Matemática | Expresión Aritmética | Resultado |
|----------------------|----------------------|-----------|
| 5 + 3                | 5 + 3                | 8         |
| 10 - 4               | 10 - 4               | 6         |
| 2 x 6                | 2 * 6                | 12        |
| $\frac{15}{3}$       | 15 / 3               | 5         |
| $2^{3}$              | 2 ** 3               | 8         |
| 13 ÷ 5               | 13 div 5             | 2         |
| 13 mod 5             | 13 mod 5             | 3         |

### ➖➖➕➕ OPERADORES DE INCREMENTO Y DECREMENTO

Los operadores de incremento (++), que aumentan el valor de su operando en una unidad, y de decremento (--), que disminuyen el valor de su operando en una unidad, son comunes en muchos lenguajes de programación. Se pueden utilizar como prefijo (antes de la variable) o como sufijo (después de la variable), lo que afecta al valor resultante de la variable. Si se utiliza como prefijo, el operador cambia el valor de la variable y devuelve este nuevo valor; si se usa como sufijo, el resultado de la expresión es el valor de la variable, y luego se modifica esta variable.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/0c442d26-135d-4b28-8b56-3876693a43d0)

### 📏 REGLAS DE PRIORIDAD

Las reglas de prioridad en expresiones aritméticas determinan el orden de las operaciones. Estas reglas son:

1. Se evalúan primero las operaciones encerradas entre paréntesis, priorizando las más internas.
2. Las operaciones aritméticas siguen un orden de prioridad: primero los paréntesis, luego los operadores unitarios (++ y --), seguidos de multiplicación, división y módulo, y finalmente suma y resta.
3. En lenguajes que admiten la operación de exponenciación, esta tiene la mayor prioridad.
4. Si hay varios operadores de igual prioridad, se sigue la asociatividad de izquierda a derecha.

Estas reglas garantizan un orden consistente en las operaciones.

| Operador          | Descripción                      |
|-------------------|----------------------------------|
| ()                | Parentesis                      |
| ++                | Incremento                      |
| --                | Decremento                      |
| *                 | Multiplicación ó producto        |
| /                 | División                         |
| %                 | Módulo                           |
| +                 | Suma                             |
| -                 | Resta                            |

recordar el orden de prioridad son:
- ()
- ++, --
- *, /, %
- +, -

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/9b7b07c5-c938-45ee-bb23-62b33304c996)

### 📚 BIFURCACIÓN
Una bifurcación es una interrupción en el flujo normal de ejecución de un algoritmo, con lo cual
la linealidad de ejecución se altera:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/a3f9ec2f-5f0a-4dda-a265-8f3480f31b12)

Las bifurcaciones pueden ser, según el punto del algoritmo donde se aplique de dos tipos: hacia
adelante o hacia atrás 

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/cdd06818-2797-4d73-a26d-6715be928712)

### 📖 BIFURCACIÓN CONDICIONAL Y LAS EXPRESIONES LOGICAS

Una bifurcación condicional depende del cumplimiento de una condición específica. En el esquema representado, la evaluación de la condición se muestra dentro de un rombo. Si la condición se cumple, el flujo de ejecución continúa por la acción F2; de lo contrario, se ejecuta la acción F1. Después de ejecutar las acciones, el flujo de ejecución continúa normalmente, como indican las flechas que se unen en el círculo. La evaluación de la condición devuelve un valor que indica si se cumple o no; por lo tanto, se necesita un tipo de datos capaz de almacenar estos valores, como VERDADERO o FALSO. 

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/2f974e7c-dc61-4269-89eb-7c6ae8c7267e)

### 📑 EL TIPO DE DATOS BOOLEAN (O LÓGICO)

El tipo de datos Boolean, también conocido como lógico, permite almacenar solo dos estados: verdadero o falso. Se define una variable de tipo Boolean de la siguiente manera: "variable: Boolean". Por ejemplo, una variable que indique si un jugador ha completado su misión en un juego se puede definir como "isMissionComplete: Boolean" o "haFinalizadoMision: Boolean". Este tipo de datos se utiliza comúnmente en inglés para los identificadores debido a su brevedad y claridad. Para asignar el valor verdadero a una variable booleana, se utiliza "verdadero", mientras que para asignar falso se utiliza "falso". Por ejemplo, para asignar verdadero a la variable "isMissionComplete", se escribiría "isMissionComplete ← verdadero"; y para asignar falso, se escribiría "isMissionComplete ← falso".

### 🧮 LOS OPERADORES RELACIONALES

Así como las expresiones aritméticas utilizan operadores aritméticos; las expresiones lógicas utilizan operadores relaciones y lógicos.

Los operadores relacionales permiten realizar comparaciones de valores de tipo numérico o
carácter. Los operadores de relación sirven para expresar las condiciones en los algoritmos y el resultado de la operación será verdadero o falso.

| Operador | Significado       |
|----------|-------------------|
| <        | Menor que         |
| >        | Mayor que         |
| = o ==   | Igual que         |
| <=       | Menor o igual que |
| >=       | Mayor o igual que |
| <> o !=  | Distinto de       |

ejemplo:

| numA | numB | Expresión Lógica | Resultado           |
|------|------|------------------|---------------------|
| 5    | 3    | 5 < 3            | Falso        |
| 10   | 4    | 10 > 4           | Verdadero    |
| 3    | 3    | 3 == 3           | Verdadero     |
| 5    | 3    | 5 <= 3           | Falso      |
| 8    | 8    | 8 >= 8           | Verdadero    |
| 7    | 5    | 7 != 5           | Verdadero     |

### 🧠 LOS OPERADORES LOGICOS

Estos operadores generalmente se van a utilizan para realizar combinaciones de expresiones
lógicas que usan operadores relacionales.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/b2909759-b2dd-4b25-a4f4-a3f302c86db2)

Estos operadores trabajan sobre un resultado booleano. Es decir, evalúan una variable booleana
o el resultado de una operación lógica basada en operadores relaciones y actúa en consecuencia
según las denominadas tablas de verdad.

#### ! Operador Lógico NO

Al aplicar el operador no, lo que hace es negar (asignar el valor opuesto) de a. Por lo tanto, el
resultado de no a, será falso.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/2a89462a-4cef-405e-9494-be942187b0ab)

#### && Operador Lógico Y (o conjunción)

El operador Y toma los valores que devuelven las expresiones lógicas a y b; y evalúa el resultado
en conjunto. 
Así, si tanto a como b son verdaderas, el resultado en conjunto será verdadero, caso contrario
devolverá falso

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/9ca9620b-aa5b-43bf-bfb3-f3968d06564f)

#### || El Operador Lógico O (o disyunción)

El operador O toma los valores que devuelven las expresiones lógicas a y b; y evalúa el resultado
en conjunto.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/f1dd6f48-aaa1-44b3-846b-82d947932092)
##

# 🔴 SEMANA 03
## Estructuras Iterativas

Las estructuras de control iterativas permiten repetir una o varias acciones un número específico de veces. Dentro de estas estructuras, el bloque de código que se repite se conoce como bucle, y cada repetición se llama iteración.

### 📚 CONCEPTOS
- Estructura de control iterativa: es un tipo de estructura de control que permite repetir
una o varias acciones (instrucciones o sentencias) un determinado número de veces.
- Bucle: se indica con este nombre a la sección de código que se repite. Es decir, dentro
de una estructura de control iterativa hay un bucle, por el cual luego de ejecutar su
última instrucción saltará a la primera de cumplirse cierta condición.
- Iteración: Cada repetición de un bucle se conoce como iteración.
- 
Al diseñar un bucle, es fundamental responder dos preguntas:
1. ¿Qué acciones se repiten?
2. ¿Cuántas veces se deben repetir?

La primera pregunta determina si se necesita una estructura iterativa y qué acciones se repiten. La segunda pregunta implica asegurar que el número de iteraciones sea finito para evitar bucles infinitos. Es crucial tener un mecanismo que garantice la finalización del bucle.

Por ejemplo, al calcular el factorial de 5 (5!), se realiza el producto de todos los números enteros del 1 al 5. Aquí, se ejecuta una operación un número finito de veces (5 veces) con una condición de parada clara.


### 📚 ESTRUCTURA ITERATIVA MIENTRAS

La estructura iterativa mientras (en inglés while) es aquella en la que el bucle se repite
mientras se cumple una determinada condición. Cuando se ejecuta la instrucción mientras,
la primera cosa que sucede es que se evalúa la condición (una expresión lógica o booleana).
Si el resultado de la evaluación devuelve falso, no se ejecutará el bucle continuando la ejecución
del algoritmo fuera de la estructura mientras (se dice que salta hacia afuera del
fin_mientras). Si la expresión booleana retorna verdadero, entonces se ejecuta el bucle y
al llegar al final de este se procederá a evaluar nuevamente la expresión booleana.
Por lo tanto, las iteraciones se sucederán una tras otra mientras la expresión booleana
(condición) siga retornando el valor verdadero. A continuación, se esquematiza la estructura de
control iterativa mientras

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/234aabc0-04f3-4df0-8751-0437cd17d846)

### 📑 UNA VARIABLE CON OBJETIVO ESPECÍFICO: EL CONTADOR

Una variable con un propósito específico en estructuras de control iterativas es el contador. El contador se utiliza para rastrear el número de iteraciones en un bucle. Su función principal es mantener un registro del progreso del bucle, aumentando o disminuyendo su valor en cada iteración. Esto permite controlar el número de repeticiones y determinar cuándo detener el bucle. El contador es esencial para estructuras como los bucles for y while, donde su valor se actualiza en cada ciclo hasta que se alcanza una condición de salida específica.

### 📚 ESTRUCTURA ITERATIVA HACER-MIENTRAS

El bucle mientras evalúa la expresión al comienzo del bucle de repetición; siempre se utilizan
para crear bucle pre-test. Los bucles pre-test se denominan también bucles controlados por la
entrada. En numerosas ocasiones se necesita que el conjunto de sentencias que componen el
cuerpo del bucle se ejecute al menos una vez sea cual sea el valor de la expresión o condición
de evaluación. 

Estos bucles se denominan bucles post-test o bucles controlados por la salida. Un caso típico es
el bucle hacer-mientras (do-while).

El bucle hacer-mientras es análogo al bucle mientras y el cuerpo del bucle se ejecuta
una y otra vez mientras la condición (expresión booleana) sea verdadera. Existe, sin embargo,
una gran diferencia y es que el cuerpo del bucle está encerrado entre las palabras reservadas
hacer y mientras, de modo que las sentencias de dicho cuerpo se ejecutan, al menos una
vez, antes de que se evalúe la expresión booleana. En otras palabras, el cuerpo del bucle siempre
se ejecuta, al menos una vez, incluso aunque la expresión booleana sea falsa.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/31d19624-1db7-4183-b9d7-fab7777497bf)

### 📚 ESTRUCTURA ITERATIVA PARA

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/1e79b484-2901-4e93-b6ec-08b16eb26f78)

La estructura del bucle for comienza con un valor inicial (vi) de la variable de índice (v), y las acciones especificadas se ejecutan mientras el valor inicial sea menor o igual al valor final (vf).
La variable de índice (vi) se incrementa en uno por defecto, o por un valor mayor según lo indicado por incr. Si este nuevo valor no excede el valor final (vf), las acciones se ejecutan nuevamente.
Por lo tanto, las acciones dentro del bucle se repiten para cada valor de la variable de índice desde el valor inicial hasta el valor final, con el incremento indicado en incr.
El incremento de la variable de índice suele ser 1 por defecto, pero puede ser diferente, positivo o negativo, según lo especificado.
Normalmente, la variable de índice es de tipo entero y se suelen usar letras como i, j, k como nombres.
El formato de la estructura del bucle for varía si se desea un incremento distinto a 1, ya sea positivo o negativo (decremento).

## ⌨️ PROGRAMACIÓN CON PROCESSING

### 📦 VARIABLES

Las variables son elementos fundamentales en la computación y en la programación. Permiten almacenar valores durante la ejecución de un programa y pueden modificarse según sea necesario. Cada variable está asociada a un espacio físico en la memoria del ordenador, tiene un nombre único llamado identificador, y puede contener diferentes tipos de datos, como números, texto, o valores lógicos.
El identificador de la variable, elegido por el programador, debe ser descriptivo y no puede coincidir con palabras reservadas del lenguaje de programación. Por otro lado, el valor almacenado en la variable debe ser definido previamente, es decir, se debe especificar qué tipo de dato contendrá la variable, como números enteros, decimales, texto, o valores lógicos.

### 📚 TIPOS DE DATOS EN PROCESSING

Processing ofrece varios tipos de datos para almacenar diferentes tipos de información. Estos se dividen en dos categorías principales: primitivos y tipos de referencia. En este momento, nos centraremos en los primitivos.

1. **int**: Representa enteros de 32 bits con un rango desde -2.147.483.648 hasta 2.147.483.647.
2. **float**: Almacena números con punto decimal, con un rango desde aproximadamente -3.4 × 10^38 hasta 3.4 × 10^38.
3. **char**: Permite almacenar caracteres individuales, como letras o símbolos, en el formato Unicode.
4. **boolean**: Solo puede almacenar dos valores: `TRUE` o `FALSE`, útil para controlar el flujo de los programas.
5. **color**: Permite almacenar colores codificados en números hexadecimales.

Estos tipos de datos son fundamentales para definir variables y realizar operaciones en programas de Processing. Cada tipo tiene un rango de valores específico y se utiliza según las necesidades del programa.


### 📖 LAS VARIABLES PREDEFINIDAS (O DEL SISTEMA)

Processing proporciona varias variables predefinidas que pueden ser utilizadas directamente en los programas sin necesidad de declararlas. Estas variables son útiles para obtener información sobre la ventana de trabajo, la interacción del usuario y otros aspectos del entorno de ejecución. Algunas de las variables predefinidas más importantes son:

1. `width`: Almacena el ancho de la ventana de trabajo.
2. `height`: Almacena el alto de la ventana de trabajo.
3. `frameRate`: Guarda la velocidad de ejecución del programa.
4. `frameCount`: Contiene el número de frames ejecutados desde el inicio del programa.
5. `displayHeight`: Almacena el alto de la pantalla completa.
6. `displayWidth`: Almacena el ancho de la pantalla completa.
7. `key`: Contiene el valor de la tecla recientemente oprimida.
8. `keyCode`: Detecta teclas especiales como flechas o teclas modificadoras.
9. `keyPressed`: Es verdadero si alguna tecla está siendo oprimida.
10. `mouseX`: La coordenada horizontal del mouse dentro de la ventana de trabajo.
11. `mouseY`: La coordenada vertical del mouse dentro de la ventana de trabajo.
12. `pmouseX`: La posición horizontal del mouse en el frame anterior.
13. `pmouseY`: La posición vertical del mouse en el frame anterior.
14. `mousePressed`: Indica si el botón del mouse está siendo oprimido.
15. `mouseButton`: Detecta qué botón del mouse fue seleccionado.
Estas variables simplifican el desarrollo de programas en Processing al proporcionar información relevante sobre la interacción del usuario y el entorno de ejecución.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/9663e264-976d-4168-97e4-0ba2a9ec934f)


### 📚 LAS ESTRUCTURAS DE CONTROL CONDICIONALES

En Processing, las estructuras de control condicionales son herramientas fundamentales para dirigir el flujo de ejecución de un programa basado en condiciones específicas. Estas estructuras incluyen:

1. **Estructuras Condicionales Simples:**
   - Permiten tomar decisiones basadas en una única comparación.
   - Se utilizan para ejecutar un bloque de código si una condición es verdadera.
   - La sintaxis básica es:
     ```java
     if (condicion) {
         // Bloque de código a ejecutar si la condición es verdadera
     }
     ```

2. **Estructuras Condicionales Dobles:**
   - Permiten elegir entre dos opciones basadas en el cumplimiento de una condición.
   - Se ejecuta un bloque de código si la condición es verdadera y otro si es falsa.
   - La sintaxis básica es:
     ```java
     if (condicion) {
         // Bloque de código a ejecutar si la condición es verdadera
     } else {
         // Bloque de código a ejecutar si la condición es falsa
     }
     ```

3. **Estructuras Condicionales Múltiples Anidadas:**
   - Permiten evaluar una expresión contra múltiples resultados posibles.
   - Se utilizan múltiples `else if` después de un `if` para evaluar varias condiciones.
   - La estructura es:
     ```java
     if (condicion1) {
         // Bloque de código a ejecutar si la condición1 es verdadera
     } else if (condicion2) {
         // Bloque de código a ejecutar si la condicion2 es verdadera
     } else {
         // Bloque de código a ejecutar si ninguna de las condiciones anteriores es verdadera
     }
     ```

Además, en Processing se utilizan operadores lógicos como `&&` (AND) y `||` (OR) para realizar evaluaciones lógicas combinadas.

### || && ! LOS OPERADORES LÓGICOS

Los operadores lógicos permiten hacer una evaluación unificada, dado un conjunto de
expresiones lógicas. Los operadores lógicos que ofrece Processing son:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/663e1579-896f-422e-9055-ac9864294e3a)

- El &&: La conjunción es un operador que opera sobre dos valores de verdad.
Típicamente los valores de verdad de dos condiciones, devolviendo el valor de verdad
verdadero cuando ambas proposiciones son verdaderas, y falso en cualquier otro caso.
Es decir que es verdadera cuando ambas son verdaderas. La tabla de verdad de la
conjunción es la siguiente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/bbfdcb3d-4eb9-4fbf-a830-31764724ddcb)

- El ||: La disyunción es un operador que funciona sobre dos valores de verdad,
típicamente los valores de verdad de dos condiciones, devolviendo el valor de verdadero
cuando una de las proposiciones es verdadera, o cuando ambas lo son, y falso cuando
ambas son falsas.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/3385b998-d52b-470e-889b-049526b5a881)

### 📖 FUNCIÓN RANDOM

La función random() se refiere al proceso de aleatoriedad. Este término se asocia a todo proceso
cuyo resultado no es previsible más que por azar. El resultado de todo suceso aleatorio no puede
determinarse en ningún caso antes de que este se produzca. En computación, la función
random() es capaz de generar un número flotante aleatorio dado un rango de valores
proporcionado. 

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/9ca3a43a-d808-4c5f-98ec-4f71cbec2279)

### 🔁 ESTRUCTURA DE CONTROL ITERATIVAS

En cuanto a las estructuras de control iterativas, existen dos principales en Processing:

1. **La Instrucción `while`:**
   - Permite repetir un bloque de código mientras se cumpla una condición.
   - La estructura básica es:
     ```java
     while (condicion) {
         // Bloque de código a repetir mientras la condición sea verdadera
     }
     ```

2. **La Instrucción `for`:**
   - Se utiliza cuando se conoce de antemano el número de veces que se debe repetir un bloque de código.
   - La estructura básica es:
     ```java
     for (inicialización; condición; actualización) {
         // Bloque de código a ejecutar mientras se cumpla la condición
     }
     ```

Estas estructuras de control son esenciales para dirigir el flujo de ejecución de un programa y tomar decisiones basadas en condiciones específicas. También facilitan la repetición de bloques de código, lo que permite una programación más eficiente y estructurada.

##PROGRAMACIÓN CREATIVA

El avance de las tecnologías digitales ha impactado en el desarrollo personal y profesional, incluyendo a los artistas y diseñadores. La integración de la programación y el arte es esencial en el diseño de videojuegos, y aprender programación usando herramientas creadas por diseñadores puede ser beneficioso.

### 🧠 La programación creativa:
La programación creativa es un movimiento que establece que los lenguajes de programación
se conciben como medios creativos, a la altura de la música, la danza o la pintura.
En este enfoque los lenguajes de programación son considerados un nuevo estándar
internacional para crear aplicaciones en cualquier parte del mundo y para cualquier parte del
mundo. Esto se torna mucho más visible en el mundo del desarrollo de videojuegos, donde se
mezcla el arte y la programación para crear expresiones de sensaciones. Los videojuegos son un
medio para transmitir sensaciones por medio de la inmersión (la experiencia cierta de poder
expresarse dentro de un mundo ficticio).

### ✍️ El código creativo:
El centro de la programación creativa es el código creativo, donde el código de la computadora se trata como un medio creativo natural. La forma en que se resuelve un problema es tan importante como la solución en sí misma. La programación creativa utiliza bases de matemáticas, física, computación y teoría artística para encontrar soluciones interesantes y novedosas.

El centro de la programación creativa es el código creativo, el cual se define como

**`𝑐ó𝑑𝑖𝑔𝑜 𝑐𝑟𝑒𝑎𝑡𝑖𝑣𝑜 = 𝑎𝑟𝑡𝑒 + 𝑐𝑖𝑒𝑛𝑐𝑖a`**

### Combatir prejuicios:
La programación creativa busca combatir prejuicios sobre las ciencias de la computación, promoviendo el "aprendizaje haciendo" a través de la construcción de bocetos de código creativo. Se desafía la idea de  que sostienen que las mismas son difíciles, aburridas y oscuras o solo para ciertos tipos de personas, y se fomenta la exploración creativa y el descubrimiento en el proceso de aprendizaje.

### 📚 QUE ES PROCESSING

**Es un entorno de programación open source (código abierto) basado en el lenguaje de programación Java para gente creativa. La premisa es que no es necesario que estas personas**

### 💡ENFOQUE PEDAGÓGICO CON PROCESSING

Processing fue creado para enseñar los fundamentos
de la programación computacional dentro de un
contexto visual para servir como software de bocetos
y ser usado como herramienta de producción.

El modelo de bocetos de la herramienta es totalmente
compatible con el modelo de conceptos que se utiliza
para diseñar videojuegos; por lo cual resulta apropiado
para la enseñanza de los principios básicos de la
programación. Y es que resulta que el documento de
conceptos es la primera referencia del juego para el
equipo de desarrollo. En él detallamos la visión general del juego y nos permitirá tener una idea
clara de los objetivos que queremos alcanzar.
## 

# 🟡 SEMANA 04
## 🧠 CONCEPTO PARADIGMA
El estadounidense **Thomas Kuhn**, los define como:

**`La serie de prácticas que trazan los lineamientos de una disciplina científica a lo largo de un cierto lapso temporal. El éxito de un paradigma es consecuencia de su efectividad para resolver algún problema.`**

Las prácticas hacen referencia a:

- **Las leyes establecidas y los supuestos teóricos.** Por ejemplo, las leyes de movimiento
de Newton forman parte del paradigma newtoniano y las ecuaciones de Maxwell
forman parte del paradigma que constituye la teoría electromagnética clásica.

- **El instrumental y las técnicas instrumentales** necesarias para hacer que las leyes del
paradigma se refieran al mundo real. La aplicación en astronomía del paradigma
newtoniano requiere el uso de diversos telescopios, junto con técnicas para su
utilización y diversas técnicas para corregir los datos recopilados.

- **Los principios generales propios** del paradigma que guían el trabajo dentro del
paradigma. Por ejemplo, para construir una un puente, se deben seguir ciertos pasos,
medidas y métodos preestablecidos para garantizar que el trabajo se realice de manera
correcta.

Respecto del **lapso temporal**, se hace referencia a que los paradigmas son el resultado de un proceso social en el que un grupo de individuos desarrolla nuevas ideas y establece principios y prácticas en torno a esas ideas. Se destaca que un paradigma puede ser efectivo para explicar ciertos aspectos del mundo, pero puede ser inaplicable u obsoleto para otros fenómenos, lo que sugiere la posible existencia de otros paradigmas más adecuados. Este fenómeno se interpreta como una consecuencia natural del proceso de evolución o maduración del concepto. Se ilustra este punto con un ejemplo en la programación de videojuegos, donde se plantea que pueden existir múltiples paradigmas aplicables y que algunos pueden ser más adecuados que otros para diferentes tipos de problemas.

En las ciencias sociales, un paradigma se utiliza
para explicar la forma en que se entiende el
mundo. Se emplea para mencionar a todas
aquellas experiencias, creencias, vivencias y
valores que repercuten y condicionan el modo en
que una persona ve la realidad y actúa en función
de ello.

De esta manera para brindar una definición formal, se considera paradigma a:
- Los marcos de referencia que imponen reglas sobre cómo se deben hacer las cosas,
indican qué es válido dentro del paradigma y qué está fuera de sus límites. Un paradigma
distinto implica nuevas reglas, elementos, límites y maneras de pensar, o sea implica un
cambio.
- Patrones de pensamiento para la resolución de problemas. Un modelo o esquema
fundamental que organiza nuestras opiniones con respecto a algún tema en particular.
Los paradigmas establecen límites adoptados por los miembros de una comunidad
científica para resolver problemas sustentados por los principios, leyes, supuestos
teóricos y técnicas que la conforman.

### 🗃️ ELEMENTOS DE LOS PARADIGMAS
Sin entrar en detalles, los paradigmas se sustentan en teorías, creencias, valores, leyes, técnicas
e hipótesis. Debido a esta formalidad, este último esquema intenta diferenciar conceptos que
normalmente son confundidos con paradigmas

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/84463e50-2918-4da4-9384-4b840e39168e)



### 📚 PARADIGMAS DE PROGRAMACIÓN
## 📚📚 Caracteristicas de PARADIGMAS: 

`**1ra Característica de paradigma:** Los objetos son contenedores de la
información y la funcionalidad que se pueden programar.`

`**2da Característica del Paradigma:** Los objetos interactúan, colaborando
para que el programa cumpla su objetivo.`

 `**3ra Característica del Paradigma:** Los
objetos se crean a partir de clases.`


Existen diferentes concepciones para los paradigmas de programación:

- **Un proceso de diseño que va más allá de una
gramática, reglas semánticas y algoritmos.** Es un
conjunto de métodos sistemáticos aplicables en
todos los niveles del diseño de programas.
Representan un enfoque particular o filosofía
para la construcción del software.

- **Son propuestas tecnológicas adoptadas por la
comunidad de desarrolladores que se enfocan a
resolver uno o varios problemas definidos y
delimitados.**

- **Es un modelo básico de diseño y desarrollo de programas, que permite producir
programas con unas directrices específicas**, tales como: estructura modular, fuerte
cohesión, alta rentabilidad, etc.

- **Es una colección de modelos conceptuales que en conjunto modelan el proceso de
diseño y determinan la estructura de un programa.** Esa estructura conceptual de
modelos está pensada de forma que los modelos determinan la forma correcta de los
programas y controlan el modo en que el desarrollador piensa y formula soluciones, que
luego son implementadas en un lenguaje de programación.

- **Provee y determina la visión y métodos de un programador en la construcción de un
programa o subprograma.** Diferentes paradigmas resultan en diferentes estilos de
programación y en diferentes formas de pensar la solución de problemas (con la
solución de múltiples “problemas” se construye una aplicación o producto de software).

Existen tres cuestiones para tener en cuenta respecto de los paradigmas de programación:

1. Ningún paradigma es mejor que otro, sino que cada uno tiene ventajas y desventajas.
También hay situaciones donde un paradigma resulta más apropiado que otro.
2. Para que las características esenciales del paradigma sean efectivamente aplicadas, las
características del lenguaje de programación utilizado para implementar la aplicación
deben reflejar adecuadamente los modelos conceptuales de ese paradigma. Cuando un
lenguaje refleja bien un paradigma particular, se dice que soporta el paradigma, y en la
práctica un lenguaje que soporta correctamente un paradigma, es difícil distinguirlo del
propio paradigma.
3. Los lenguajes de programación están basados en uno o más paradigmas, por ejemplo:
Processing está basado en el paradigma orientado a objetos. El lenguaje de
programación Scheme, en cambio, soporta solo programación funcional. Otros
lenguajes, como C++ y Python soportan múltiples paradigmas.

### 😃 EL PARADIGMA ORIENTADO A OBJETOS DE MANERA RESUMIDA

El paradigma de programación orientada a objetos, que se fundamenta en la idea de representar problemas y soluciones de manera similar al procesamiento de información del cerebro humano. En este paradigma, los problemas y soluciones se representan como entidades llamadas objetos, que poseen atributos almacenados en variables especiales y operaciones que actúan sobre esos atributos mediante algoritmos específicos.

Los objetos se comunican entre sí a través de mensajes, estableciendo relaciones según un conjunto de reglas y normas definidas en el protocolo de mensajes. Este paradigma se sustenta en cuatro pilares:** abstracción, encapsulación, herencia y polimorfismo.** Estos pilares estructuran la creación, uso y destrucción de objetos mediante clases, y establecen un contrato entre clases para la implementación de operaciones. Además, definen formalmente qué es un objeto, cómo se modelan y cómo se optimiza la reusabilidad y mantenimiento del código.

### ✍️ EL MODELADO Y LA ABSTRACCIÓN EN EL PARADIGMA ORIENTADO A OBJETOS

El modelado es una técnica que consiste en
representar información mediante un modelo. Un
modelo es una abstracción de una realidad. El
término abstracción hace referencia al proceso de
centrarse únicamente en los detalles relevantes del
fenómeno estudiado o que es objeto de
observación.
La abstracción es también, una de las propiedades del paradigma orientado a objetos; esto
significa que el paradigma orientado a objetos buscará a través de esta propiedad:

- Abstraer un problema (determinar los aspectos relevantes del problema resolver) para
luego realizar una,
- abstracción de la solución de ese problema (determinar los aspectos relevantes de la
solución que se propone como solución al problema) y finalmente
- construir una abstracción del sistema informático creado. Esto significa que los aspectos
relevantes del producto sean programados, probados y documentados en la forma de
clases y sus interrelaciones, para que otros desarrolladores puedan interpretarlos.

### 🧠 CARACTERISTICAS DEL MODELADO
El modelado ofrece 4 características esenciales:

1) Una visualización de un sistema: tanto del
problema a solucionar como de la solución. En
ambos casos estamos refiriéndonos a una
aproximación (en el primer caso una
aproximación de los objetos de nuestro juego y
como ellos interactúan, mientras que del
segundo caso un esquema y documentación del software del videojuego)
2) Una especificación de su comportamiento: nos permite indicar detalladamente como
actúa el mismo ante diferentes situaciones.
3) Una plantilla que guíe a los desarrolladores durante su construcción: es decir son los
“planos” que el arquitecto del software sigue para construir el producto.
4) Documentar decisiones de diseño: siempre las decisiones de diseño deben estar bien
documentadas y justificadas. En algunas metodologías la documentación se dejaba al
último; o como sucede de forma muy habitual está la tentación de no documentar por
el tiempo que incurre. Los modelos permiten minimizar el tiempo de documentación. 

### 🧠🧠 LOS semana  DE LA ABSTRACCIÓN DE OBJETOS

El modelo orientado a objetos permite construir una representación para analizar, describir,
explicar simular o predecir un fenómeno y se sustenta alrededor de las siguientes definiciones:
- **Clase:** modelo, molde, plano o maqueta a partir del cual se pueden generar objetos. Las
clases son entidades utilizadas para analizar el problema y diseñar la solución. Toda clase
posee 3 elementos importantes: el nombre de la clase, los atributos y las operaciones. Mediante las clases se pueden determinar los actores (clases) que participan en el
problema estudiado (o en la solución) así como las características y acciones que estas
entidades poseen y que contribuyen de alguna manera para que se cumplan los
objetivos abordados por la solución planteada (los requisitos). Las clases son
programadas en un lenguaje de programación orientado a objetos.

- **Objeto**: Los programas se ejecutan en memoria, adoptando el nombre de procesos. En
el caso de los programas orientados a objetos estos procesos se denominan objetos que
adquieren los atributos y operaciones de la clase a partir de la cual se ha creado, de esta
manera en memoria pueden existir muchos objetos generados a partir de la misma clase
pero cada una con su propia identidad que la separa de las demás (esto puede
asemejarse al hecho de que a partir de un mismo plano se pueden construir varias
viviendas, todas iguales por las especificaciones del plano pero en definitiva cada una
es una construcción individual)
- **Relaciones:** Indica la forma en que los objetos colaboran entre ellos para realizar alguna
tarea específica. Esto genera un nuevo concepto que es el mensaje: es el mecanismo
por el cual un objeto en memoria solicita a otro que ejecute una operación. Entonces
las relaciones indican la forma en que los objetos envían mensajes a otros objetos.
- **Interfaz:** Las operaciones de un objeto que pueden ser solicitadas por otro objeto se
denominan servicios. Para que los servicios de un objeto puedan ser invocados por otro
objeto; el objeto que desea ponerlos a disposición de los otros objetos debe definir una
interfaz. La interfaz es simplemente un mecanismo por el cual se determina si una
operación se halla disponible para ser invocada por otro objeto (las operaciones dentro
del objeto siempre son servicios para las otras operaciones del mismo objeto, esto es,
las operaciones de un objeto siempre pueden ser invocadas por las otras operaciones
del mismo objeto). El concepto de interfaz también se aplica a los atributos, esto es; si
no se especifica una interfaz para un atributo, el mismo no podrá estar disponible para
otros objetos.

## LA ABSTRACCIÓN DE LAS CLASES 

**Introducción a la abstracción en el paradigma orientado a objetos**

La abstracción, piedra angular del paradigma orientado a objetos, es un proceso crucial para identificar las características esenciales y los comportamientos comunes de una parte de la realidad. Este proceso permite definir las entidades que representan el sistema estudiado y es fundamental en el análisis y diseño orientado a objetos, ya que facilita la determinación de las clases que modelan el problema a resolver.

### **La importancia de la clase como entidad fundamental**

La clase, entendida como una entidad que describe un conjunto de objetos con estructura y comportamiento similares, es un concepto central en la programación orientada a objetos. Se asemeja a un "molde" del cual se pueden crear múltiples objetos del sistema informático. Esta analogía con los moldes para hornear ilustra cómo las clases permiten obtener objetos con características específicas.

### **Principio de abstracción: distinción, focalización y clasificación**

El principio de abstracción en el paradigma orientado a objetos se basa en tres premisas fundamentales: distinguir diferentes objetos, focalizarse en las características y operaciones esenciales de esos objetos, y clasificar los objetos en base a sus características y operaciones comunes en clases. Este principio refleja un proceso natural que todos aplicamos en nuestra vida cotidiana al diferenciar entre diversos tipos de objetos y enfocarnos en sus propiedades esenciales.

**Aplicación del principio de abstracción en situaciones cotidianas**

Desde la infancia, aprendemos a clasificar objetos y a distinguir entre ellos. Ya sea diferenciando entre seres vivos y objetos inanimados o identificando herramientas y juguetes, ejercemos la capacidad de abstracción de manera intuitiva. Además, en nuestras actividades diarias, como practicar un deporte, aplicamos la abstracción al centrarnos en las propiedades esenciales comunes de los objetos involucrados, como compañeros de equipo, pelotas y objetivos del juego.

**Importancia de la abstracción en el desarrollo de videojuegos**

La abstracción juega un papel crucial en el desarrollo de videojuegos. Cada elemento de un juego, desde personajes hasta objetos y entornos, se representa mediante clases que definen su estructura y comportamiento. Estas clases son la base para la creación de los GameObjects, que son los objetos individuales en el juego.

**Ejemplo práctico: identificación de clases en una pantalla de juego**

En una pantalla de juego, cada elemento visible está respaldado por clases que representan su funcionalidad y apariencia. Al identificar estas clases junto con sus atributos y operaciones, podemos entender cómo se generan los GameObjects y cómo interactúan en el juego.

### **Modelado de la abstracción: Introducción al Diagrama de Clases en UML**

El modelado de la abstracción de objetos se lleva a cabo mediante el uso de diagramas estandarizados, siendo el Diagrama de Clases de UML (Unified Modeling Language) uno de los más prominentes. Este diagrama es fundamental para especificar la estructura de datos de un sistema de información en el ámbito del modelado orientado a objetos.

### 👪 **Familias de Diagramas en UML**

UML ofrece dos grandes familias de diagramas: los diagramas de estructuras y los diagramas de comportamiento. Los primeros se centran en la arquitectura de datos del sistema, mientras que los segundos se enfocan en especificar su comportamiento.

### 🗃️ **Diagramas de Clase: Aspectos Generales**

El Diagrama de Clases es esencial en UML, ya que se utiliza principalmente para definir la estructura de datos de un sistema. Este diagrama constituye la base de cualquier solución en el modelado orientado a objetos, ya que incluye el conjunto de clases que conforman la estructura básica del sistema y distribuye los datos que maneja a través de sus atributos.

Análogamente al cuerpo humano, donde las clases y sus atributos representan el esqueleto del sistema, el Diagrama de Clases también permite definir los "músculos" que permiten la movilidad del sistema, es decir, las operaciones y relaciones entre clases que determinan su funcionamiento.

### 📖 **Representación de Clases en UML**

En un Diagrama de Clases, una clase se representa como una caja que puede dividirse en una, dos o tres partes. La primera parte siempre indica el nombre de la clase. Si la clase se divide en tres secciones, la segunda parte corresponde a los atributos y la tercera a las operaciones. En caso de que la clase solo tenga dos secciones, la segunda puede referirse tanto a los atributos como a las operaciones.

**Ejemplo Práctico: Clase Avión en UML**

Para ilustrar este concepto, consideremos la clase Avión. En el diagrama, se representa explícitamente las tres partes de la clase: nombre (Avión), atributos (modelo, cantidad de motores, velocidad y capacidad) y operaciones (acelerar y girar en una dirección). Este ejemplo muestra cómo se modela una clase en UML y cómo se pueden definir objetos a partir de ella.


![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/c28c85d4-6b14-4101-a3a3-c4c860ec2e6d)


**En conclusión, el Diagrama de Clases en UML es una herramienta fundamental para el modelado de la abstracción en la programación orientada a objetos, permitiendo representar la estructura de datos de un sistema y definir sus relaciones y comportamientos de manera clara y concisa.**

### 📏📏 ** Nomenclatura para la Definición de Nombres de Clases**

1. Los nombres de las clases deben ser sustantivos en singular.
2. La primera letra del nombre debe comenzar en mayúscula, seguida de letras minúsculas.
3. No se permiten espacios en los nombres. Durante la fase de análisis en UML, se puede usar guion bajo (_) para separar palabras en el nombre de la clase. Sin embargo, durante la fase de diseño, es una práctica común que la primera letra de cada palabra subsecuente esté en mayúscula. Esta última recomendación se aplicará en todos los diagramas de clases realizados en la asignatura.

**Características Avanzadas de una Clase: Visibilidad**

Además de los elementos básicos como el nombre, atributos y operaciones, una clase también cuenta con propiedades avanzadas que permiten especificar aspectos más detallados de la clase modelada. Entre estas propiedades, la visibilidad es fundamental, ya que determina el acceso que otras clases tendrán a los atributos y operaciones de la clase.

**Definición de Visibilidad**

La visibilidad establece la disponibilidad que ofrece una clase a otras clases en cuanto al uso o acceso de sus atributos y operaciones. Se puede especificar si un atributo u operación está totalmente disponible para otras clases, o si está restringido y no disponible para ninguna otra clase. Además, existen niveles intermedios de visibilidad que pueden variar según el lenguaje de programación utilizado.

### 🎚️ **Niveles de Visibilidad en UML**

En UML, se definen cuatro niveles de visibilidad:

1. **Público (+)**: La visibilidad se extiende a otras clases, lo que significa que cualquier clase puede acceder a ese atributo u operación.

2. **Protegido (#)**: La visibilidad se extiende únicamente a las subclases de la clase original. Esto se profundizará más adelante cuando se aborde el concepto de herencia.

3. **Privado (-)**: En este nivel, solo la clase original puede acceder a los atributos y operaciones privadas.

4. **Paquete (~)**: Introducido en UML 2.5 para reflejar prácticas de algunos lenguajes de programación. La visibilidad se extiende a las clases que comparten el mismo paquete en el que se ha definido la clase original. Fuera de este paquete, otras clases no pueden acceder al atributo u operación a menos que sean subclases.


### 📒 **Definición de Atributos en UML**

La definición de un atributo en UML implica considerar varios aspectos para una descripción completa y precisa. Un atributo representa una característica específica de un objeto y es, en esencia, una variable que almacena un valor. Para una representación adecuada en UML, es esencial comprender los tipos de datos predefinidos que ofrece UML y cómo se aplican en la definición de atributos. A continuación, se presentan los tipos de datos predefinidos en UML, junto con ejemplos de su uso:

1. **Boolean**: Indica un valor lógico que puede ser verdadero o falso. Ejemplo: `isFinishedTime: boolean`

2. **Byte**: Representa un tipo numérico para enteros con un rango limitado, generalmente entre -128 y 127. Ejemplo: `cantidadVidas: byte`

3. **Short**: Indica un tipo numérico para enteros con un rango más amplio que Byte. Ejemplo: `puntajeBonus: short`

4. **Integer**: Representa un tipo numérico para enteros con rangos muy grandes. Ejemplo: `puntajeAcumulado: integer`

5. **Long**: Indica un tipo numérico para enteros mucho más grandes que Integer, típicamente utilizado en cálculos científicos. Ejemplo: `distanciaAsaturno: long`

6. **Float**: Representa un tipo numérico para números reales, útil para aplicaciones de videojuegos que manipulan decimales. Ejemplo: `resultadoOperacion: float`

7. **Double**: Indica un tipo numérico para números reales muy grandes, comúnmente utilizado en cálculos científicos. Ejemplo: `derivada: double`

8. **Date**: Representa un tipo para valores que representan fechas. Ejemplo: `fecNac: date`

9. **String**: Indica un tipo que representa cadenas de caracteres, útiles para almacenar texto. Ejemplo: `Nacionalidad: string`

10. **Char**: Representa un único carácter. Ejemplo: `teclaSeleccionada: char`

Al definir atributos en UML, es esencial considerar el tipo de dato adecuado para cada característica del objeto que se está modelando, garantizando así una representación precisa y coherente del sistema.

### 📐 **Nomenclatura para la Definición de Atributos**

La nomenclatura adoptada para la definición de atributos en esta materia sigue las convenciones del lenguaje de programación Java. A continuación, se describen las reglas que se aplicarán:

1. Los atributos deben iniciar con una letra minúscula.
2. No pueden comenzar con un número.
3. El nombre del atributo debe reflejar claramente el significado de la característica que representa en la clase. Por ejemplo, para una clase `NaveEspacial` que tiene un atributo que indica la cantidad de vidas, un nombre válido para el atributo sería `cantVidas`, mientras que nombres como `v` o `cv` serían inválidos.
4. No se permiten espacios en los nombres de los atributos. En la fase de análisis del Diagrama de Clases, se admite el uso de guion bajo (_), pero en la fase de diseño se seguirá la convención de que la primera letra de cada palabra subsiguiente esté en mayúscula.

## 📚 ** Nomenclatura para Definición de Operaciones**

Las operaciones representan acciones que pueden ser realizadas por los objetos creados a partir de una clase. La nomenclatura para la definición de operaciones en esta materia sigue las convenciones del lenguaje Java:

1. Las operaciones deben ser verbos en infinitivo.
2. Se escriben en minúscula.
3. No se admiten espacios en los nombres de las operaciones. En la fase de análisis del Diagrama de Clases, se admite el uso de guion bajo (_), pero en la fase de diseño se seguirá la convención de que la primera letra de cada palabra subsiguiente esté en mayúscula.

En un diagrama de clases, las operaciones se definen siguiendo la sintaxis:

\[visibilidad\] nombre ([lista de parámetros])[:tipo de retorno]

Los corchetes indican que estos elementos son opcionales, por lo que solo el nombre de la operación es requerido.

# ⚫ Semana 5

Las aplicaciones orientadas a objetos rara vez definen clases cuyos objetos trabajen de manera aislada. Un buen diseño utiliza objetos de diferentes clases que cooperan para alcanzar el objetivo central del dominio del negocio. Por eso, esta sección se centrará en cómo los objetos colaboran entre ellos para realizar tareas específicas y cómo representarlo en un diagrama de clases, conocidas como relaciones entre clases. Se definirán los diferentes tipos de relaciones y se darán ejemplos aclaratorios.

## ↕️ RELACIONES ENTRE CLASES
Las relaciones permiten establecer cómo interactúan las clases. En UML se representan
mediante una línea. Existen diferentes tipos de relaciones:
- ✓ Asociación
- ✓ Agregación
- ✓ Dependencia
- ✓ Implementación
- ✓ Herencia

### La asociación
Permite establecer una relación conceptual entre dos clases. Especifica una conexión entre los
objetos de una clase y los objetos de otra clase. Describiremos las características de las
asociaciones mediante ejemplos.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/89d54900-9aac-4dfe-b927-5e2aba6ce473)

La asociación establece una relación conceptual entre dos clases, conectando objetos de una clase con objetos de otra. Se representa con una línea en los diagramas y es una relación no jerárquica, conocida también como **una relación de igual a igual.** Esta relación puede ser **direccional**, indicada con una flecha, mostrando hacia qué objeto se puede navegar. Es decir, ninguna de las dos tiene
un estatus superior respecto de la otra (como sucede y se verá en la herencia, las clases
abstractas y las interfaces).
El extremo con la flecha es el** objetivo u objeto** hacia el que se puede navegar. El extremo sin la
flecha se denomina **fuente**.

### Frase semantica de asociacion:
”tiene o conoce” 
un atributo cuyo tipo es de la otra clase; esto aplicado a nuestro ejemplo sería: un equipo tiene un solo estadio. El significado conceptual también recibe
el nombre de frase semántica.

### multiplicidad

Lo que debe quedar claro es que son autoexcluyentes. Es decir, la multiplicidad de un atributo o es expresada en el atributo o es
expresada en la relación. Gráficamente, esto es

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/5f322c3a-00f5-4dee-a952-24c4e8e8c34f)

Puede observar que la relación de asociación brinda mucha información. Por ejemplo, Equipo
tiene un atributo (aunque no se lo vea definido explícitamente) y se denomina estadio.
Esto se debe a que la relación de asociación es una implementación de punteros: un objeto de
una clase apunta a uno o varios objetos de otra clase. Como se mencionó anteriormente, la
cantidad de objetos a los que apunta la fuente se define mediante la multiplicidad. Hay varios
indicadores de multiplicidad. A continuación, se los indican en la siguiente tabla:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/21c6719b-d500-4d07-8e3f-29c68292902b)

#### ¿Es posible modificar la frase semántica de la asociación?

Si, veámoslo con un ejemplo que
encara esta situación y a la vez refuerza el modo de usar la multiplicidad

Ejemplo 2: la famosa lista de power ups que puede tener un personaje. En este caso nos
remitiremos a Legend of Zelda: A Link to the Past. Observe la siguiente imagen e intente modelar
las relaciones entre Link y el conjunto de power ups que puede usar en el juego:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/84a1f076-de76-473f-86da-5fc3b48a10d0)

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/8df71e1f-9405-4388-bf5a-fc34e95fb06b)

En este modelo podemos observar muchos aspectos muy importantes a considerar para quienes
empiezan en el modelado de clases. En primer lugar, observe que la clase de la cual se obtiene
un objeto que representa a Link se denominada MainCharacter. Es un error muy común
denominar a la clase con el nombre del personaje, es decir definir una clase que se llamaría en
este caso Link; pero debe recordar que una clase es un molde del cual se generan objetos. El
proceso por el cual a partir de una clase se genera un objeto se denomina instanciación; así un
objeto es una instancia de una clase. Por tanto, no sería correcto que la clase se llame como el
objeto.

En segundo lugar, observe que es posible cambiar la frase semántica por defecto de una
asociación para expresar con mayor detalle la relación conceptual entre dos clases. Por
ejemplo, entre MainCharacter e Item se expresa la relación con la palabra “collects”; es decir
“objetos de la clase MainCharacter coleccionan objetos de la clase Item”.
Esta relación es refinada mediante la multiplicidad para indicar que “Un objeto de la clase
MainCharacter colecciona muchos objetos de la clase Item, pudiendo al inicio no poseer ningún
item”, esto significa que el * del lado de Item en realidad es equivalente a 0..*.
Además, la relación se puede refinar aún más mediante la especificación del rol de los objetos
en la relación. En este ejemplo, observe que el rol especifica el nombre del atributo que posee
o tiene la clase fuente, que en este caso es ítems. Entonces la relación queda formalmente “Un
objeto de la clase MainCharacter colecciona 0 o muchos ítems”.

Así las otras relaciones de asociación presentes en este ejemplo son:
• Un objeto de la clase MainCharacter usa 0 o muchos equipamientos
• Un objeto de la clase MainCharacter adquiere 1 o muchas habilidades

#### ¿Pueden las asociaciones ser bidireccionales?

Si, esto se aplica esencialmente cuando se desea mantener un registro de la asociación. En el
caso de los juegos se puede referir a la compra de premios mediante el uso de tarjeta. En estos
casos resulta interesante que tanto el comprador como el vendedor del premio tengan un
registro de la transacción (operación de compra).
Ejemplo 3: Intente interpretar este diagrama de clases

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/5a9aa10d-af70-4a17-92df-ccea05db3f3c)

Puede observar que la clase principal es Compra, la cual mantiene un atributo de un objeto de
tipo Tarjeta. De la clase Premio se pueden instanciar objetos, tales como aquellos que día a día
sugiere el juego que se adquieran (o aún incluso cuando no lo jugamos, especialmente en juegos
de celulares). Al autorizar una compra se guarda la fecha y… aquí viene lo interesante, Compra
mantiene un conjunto de detalles (que sería el registro de cada una de las compras realizadas),
pero a la vez cada uno de esos detalles mantiene un registro de la compra a la que pertenece;
por tanto, es una relación bidireccional. ¿Por qué no se utiliza una relación de asociación desde
Compra a Premio directamente? Porque cada objeto de tipo Premio solo puede ser comprado
por un cliente únicamente (algo similar a cuando compra un producto en un negocio: si bien hay
varios del mismo tipo en la consola o mostrador, ud selecciona alguno de ellos y es ese el
producto que adquiere). Además, el precio del premio puede cambiar en cualquier momento,
sin embargo, cuando se realiza la compra, ese precio se registra y no se cambia. Entonces,
Detalle se vuelve muy importante, porque permite llevar el registro a cuál compra pertenece,
cual es el premio comprado y con que precio adquirió el premio en el momento de la compra.
Por otra parte, un jugador podría comprar un premio y no usarlo hasta el momento que lo
requiera. Entonces ¿de dónde va a extraer el premio comprado si no es del detalle?

#### Entonces la bidirección se logra con los navegadores a ambos extremos ¿Hay otra forma de representarla?

Si, curiosamente si no coloca la navegación en ninguno de los extremos será equivalente a una
bidirección, es decir para el ejemplo anterior este sería su diagrama equivalente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/e6dfd06b-33ce-470f-b9d4-adf159b8117d)

## La agregación

La agregación es una relación de asociación, pero jerárquica, en el sentido de que se establece
que una de las clases representa un “Todo” mientras que la otra clase representa a las “Partes”
del todo. La agregación no es diferente de una asociación y se suele preferir referenciarla como
asociación.

Sin embargo, dado que el propósito de los modelos es reflejar una realidad de la manera más
fiel posible dentro de los parámetros de abstracción que se adopten, UML ofrece esta relación
para indicar explícitamente la relación conceptual entre un “todo” y sus “partes”, aunque luego
en la implementación se interpreten de la misma manera.
En definitiva, esta relación representa el hecho de que una clase puede constar de otras clases.
La jerarquía se expresa indicando la clase “todo” en la parte superior, y los componentes
“partes” por debajo de ella. Algunos autores no consideran lo anterior, debido a que la relación
indica la clase “todo” mediante un rombo o diamante denominado conector. Nuevamente se
vuelve a destacar que las clases agregadas son “atributos” de la clase completa y, por lo tanto,
no se las expresa en manera explícita porque la relación gráfica se encarga de ello.
Del lado de las “partes” la relación puede o no finalizar en una flecha. Además, como la relación
“todo” siempre se refiere a un elemento, no se coloca multiplicidad de este lado, mientras que
del lado “partes” se debe indicar explícitamente la multiplicidad.
La frase semántica que referencia una relación de agregación es “está formado/a por”. Esta
frase debería ayudar a confirmar o desestimar si una relación de asociación representa una
agregación.

Ejemplo: Analice el diagrama de clases del ejemplo 3 y discierna si las relaciones de asociación
indicadas confieren una agregación, en cuyo caso actualice el diagrama de clases.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/a6ddab2b-7d87-41a7-abfb-c655b18868c5)

Bien, el diagrama de clases anterior se ha actualizado de la siguiente manera:
- Entre Compra y Tarjeta hay una asociación. La compra ¿está formada por la tarjeta? No.
Una compra no está física o conceptualmente formada por una tarjeta, sino que registra
los datos de la tarjeta.

- Entre Compra y Detalle hay una asociación. La compra ¿está formada por detalles? Si,
una transacción (operación de compra) necesariamente “está formada” por detalles,
que son los que registran los premios comprados. Por tanto, aquí, se coloca del lado
“todo” que es Compra el conector. Así, se debe leer “Un objeto compra está formado
por 1 o muchos detalles”. Observe además que en el conector no se coloca
multiplicidad.

- Finalmente, entre Detalle y Premio también hay una asociación. Como se indicó
previamente, en un detalle se registran los premios adquiridos, pero esto no significa
que física o conceptualmente un detalle “esté formado” por un premio.

También observe que, con el objetivo de mantener la bidirección de la navegación, se ha
agregado un atributo denominado compra en Detalle, para explicitar la relación de bidirección.
Esto se ha realizado con el objetivo de mantener la claridad de lectura, aunque también se
podría haber realizado de la siguiente manera

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/0fd8a87f-696c-4108-8670-eca8b554d32e)

Así, no hace falta colocar el atributo de tipo Compra en la clase Detalle, pero tenga cuidado de
malinterpretar la multiplicidad 1 que está debajo del conector: no pertenece a este; sino que
indica que un detalle usa o conoce su compra. También, debido a que **la navegabilidad del lado
de las “partes” es opcional**, el siguiente diagrama de clases también sería válido

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/7acf0ba7-94a3-42c8-9f18-a6d3db9b3fed)

Donde se mantiene la lectura de que “un objeto de tipo Compra está formado por uno o más
detalles” y que “un detalle forma parte de una compra”. Además, un detalle usa o conoce su
compra. Esta forma, aunque parece clara podría causar una mala interpretación, tal como
sucedía con el caso anterior, por lo que se suele en realidad usar esta otra forma de expresión

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/1d72bfe4-2cf1-4f4e-b1f5-bcb8b1d3d63e)
Mientras se cumpla la nomenclatura particular, puede utilizar cualquiera de estas formas.

## La composición

Es un tipo muy representativo de una agregación, que expresa una relación más fuerte entre
el todo y sus partes. Cada componente puede pertenecer tan solo a un todo. En la composición
la clase “todo” es responsable de la creación y de la destrucción de la/s clase/s parte/s, y esta
última no puede existir en alguna otra relación al mismo tiempo. Por este motivo la composición
se denomina agregación fuerte y la agregación propiamente dicha agregación débil.
La clase compuesta debe garantizar que se crean todas sus partes y se fijan a la compuesta, antes
de que ésta esté por completo construida. En tanto exista la clase compuesta, se puede confiar
que ninguna de sus partes será destruida por cualquier otra entidad, pero cuando se destruya
la compuesta, se deben destruir las partes, o puede eliminar en forma explícita las partes y
llevarlas hacia algún otro objeto. La relación en UML se expresa mediante un símbolo similar al
de la agregación, pero el conector en este caso es un diamante con color de relleno.

Ejemplo: Observe la siguiente imagen perteneciente al juego arcade The Fast & Furious
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/4bab9c76-cf90-437f-b66c-ba7683c3a558)

Al inicio del juego y a medida que se van ganando carreras, es posible adquirir diversas partes
para mejorar el auto, entre los que se encuentra motores, nitro, neumáticos, alerones, etc.
Modele un diagrama de clases que establezca la relación entre un auto y estas partes
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/08736971-ab12-4f29-ae6c-4a184273284e)

errónea, debido a que las partes se deben crear al momento de la instanciación del objeto de
tipo Auto. Por lo tanto, lo correcto es leer literalmente “un auto está formado por muchos
neumáticos”, aunque sabemos que en un análisis necesitamos exactamente 4 neumáticos para
empezar, pero lamentablemente en UML ese tipo de multiplicidad ya no es válido.
Finalmente podemos observar el caso del alerón. En este caso podemos decir que “un auto está
formado por un alerón” o que un “alerón forma parte de un auto”. Sin embargo, podríamos
correr una carrera sin el alerón. Por ese motivo resulta claro que es una agregación débil, o
simplemente una agregación. Y la multiplicidad expresa el hecho de que podría utilizar o no un
alerón.

Nota: Finalmente para terminar con los conceptos vertidos hasta ahora, se puede expresar
gráficamente la relación que existe entre estas tres asociaciones con la siguiente gráfica, donde
la agregación y la composición son subconjuntos de asociación, lo que significa que son casos
específicos de asociación:

## La dependencia

Se lo suele definir como una **“asociación de uso”**. Esto significa que expresa una situación donde
**una clase A utiliza otra clase B, y donde un cambio en la especificación de B puede afectar a A,
pero no necesariamente a la inversa.**
Por ese motivo la relación se denomina de dependencia: **la clase A se denomina cliente,
mientras que la clase B se conoce como proveedor.** **Un objeto de la clase cliente depende de
un objeto de la clase proveedor para poder proporcionar o completar un servicio.** El símbolo
para una relación de dependencia luce como una asociación unidireccional, excepto que la línea
es punteada en lugar de continua.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/6e925d96-972e-4eee-9115-4915e2f699c0)

Esta situación expresa que, a
diferencia de las anteriores relaciones
tratadas, la dependencia no opera con punteros. Es un recurso que sirve para mantener la estructura de clases con el menor nivel de
relacionamiento posible, es decir su objetivo consiste en contribuir en el diseño de un modelo
con bajo **acoplamiento.** El acoplamiento es una medida que indica cuan relacionadas están las
clases. Si las clases están muy relacionadas, se dice que tienen un alto acoplamiento, como
consecuencia de esto, cualquier cambio en ambas clases puede afectar seriamente a la otra
clase dificultando la posibilidad de modificar, actualizar o mejorar el funcionamiento del
sistema, lo cual no es deseado. El acoplamiento no se puede evitar, porque para que el sistema
realice su objetivo requiere que los objetos interactúen entre ellos, pero si se debería minimizar.

**Cada vez que se establece una relación de asociación, se establece un puntero entre dos clases.
Esto genera acoplamiento, y una relación bidireccional genera aún mayor acoplamiento.**

Por este motivo, **para evitar la bidirección cuando se necesita una visibilidad invertida, se
aplican dependencias.** La dependencia** se implementa mediante un concepto denominado
visibilidad por parámetros.** Esto significa que la operación del cliente debe especificar que uno
de los parámetros sea un objeto del servidor.

De esta manera el cliente “visualizará” el servidor únicamente mientras dure el tiempo de vida
de la operación, momento en el cual la visibilidad desaparece.

Entonces si bien existe el acoplamiento, es mucho más débil que aquel que se generaría si se
estableciera una bidirección como consecuencia la creación de un puntero.
Las dependencias suelen aparecer cuando ud ya ha modelado su diagrama de clases y está a
punto de programarlo, o cuando quiere visualizar sus clases programadas en la forma de un
diagrama de clases. Esto significa que, si su diagrama de clases presenta dependencias, su
modelo está en etapas avanzadas y generalmente representan las clases programadas.

Ejemplo: Considerando lo que indica el apartado anterior, se debe procurar un modelado
intentando evitar usar relaciones bidireccionales. Entonces usando la dependencia, retome el
ejemplo 6 y elimine el acoplamiento generado por la bidirección provocada por la agregación
entre Compra y Detalle.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/7c60f668-8ef5-4918-b4b0-21acd6ba833f)

Observe que se ha reemplazado la agregación bidireccional entre Compra y Detalle (que produce
un alto acoplamiento) por una asociación unidireccional y una dependencia. Desde Detalle hacia
Compra se mantiene la asociación, ya que es necesario que cada Detalle sepa a que Compra
pertenece. Mientras que del otro lado, Compra ahora no mantiene una relación con Detalle, por
lo cual ¿cómo obtiene el total de la compra? Ahora posee una operación denominada
obtenerTotal() que recibe por parámetro un objeto de tipo BuscadorDeCompras. Esta clase
posee una colección de objetos con todos los detalles existentes y además ofrece una operación
por medio de la cual, si se le pasa el código de la compra, podrá devolver los detalles de esta. Al
recibir por parámetro el buscador de compras, una compra podrá consultar cuales son sus
detalles y de esa manera obtener el total de la compra. La relación de dependencia sale de una
operación de la clase “Cliente” (la clase Compra) y para que se puede ejecutar requiere (o es
dependiente) de una clase “Proveedora” (en este caso BuscadorDeCompras).

#### Un uso importante de la dependencia: la gestión de colisiones

En el mundo de los videojuegos, la interacción entre los objetos se conoce en primera instancia
como colisión. Esto es, dos o más objetos se encuentran en un mismo espacio de la pantalla. La
interacción de cada uno de ellos puede ser diferente: hablar, golpear, defenderse, explotar, etc.
Si ud programa juegos usando un lenguaje de programación puro y el paradigma orientado a
objetos, una manera de gestionar estas interacciones es crear clases que mantengan una
colección de objetos del mismo tipo y usar la dependencia para determinar alguno de los objetos
de esta colección colisiona con otros objetos.

Ejemplo: Observe la siguiente imagen. 
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/a857fcb1-4ae3-409c-b65d-239469fa0df4)

Pertenece al juego Galaga. En este juego, al inicio de
cada nivel los enemigos se van ubicando en su posición original
en el espacio. Luego de que se forman empiezan a atacar ya sea
impactando sus disparos contra nuestra nave o chocándola, lo
cual genera la pérdida de una vida.
Por otro lado, mientras se forman nosotros podemos atacarlos
disparándoles (tal como lo muestra la imagen). Cada disparo
que realizamos viaja por el espacio. Este disparo puede
impactar en un enemigo o desaparecer de la pantalla.
Realice un diagrama de clases que permita gestionar la
ubicación de cada enemigo generado y evaluar si nuestros
disparos impactan contra alguno de ellos. De la misma manera
valide si nuestra nave choca con un enemigo o si el disparo de
uno de ellos impacta contra ella. 

El siguiente diagrama de clases muestra parcialmente el modelado solicitado.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/91c1307e-419c-4915-9d52-d80a568f4386)

Observe que hemos creado dos clases que serán los contenedores de una colección de objetos.
En primer lugar, se genera una colección de enemigos, representada por la clase ListaEnemigos.
Esta clase posee un atributo denominado enemigos que es de tipo Enemigo.
En segundo lugar, se genera una colección de los disparos que nuestra nave realiza, denominada
GestorDisparos, que posee un atributo denominado disparos que es de tipo Disparo.
Tanto Nave, como Enemigo y Disparo poseen un atributo denominado posición que es del Tipo
Position, el cual posee las coordenadas en el plano. Esta clase está etiquetada con el estereotipo
<<type>> por lo cual sabemos que es usada para generar un tipo de datos no existente en UML.

Ahora observemos el funcionamiento de este diagrama de clases:

- Un objeto de tipo Nave puede realizar una operación denominada disparar(). Cada vez
que se dispara se agrega un nuevo objeto de tipo Disparo al gestor de disparos
(seguramente se invoca la operación agregarDisparo()). Para poder realizar esto, la
única manera de hacerlo es que la operación disparar() reciba como parámetro el
gestor de disparos.

- Los disparos almacenados en el gestor de disparos van actualizando su posición
constantemente. Por ese motivo se debe invocar en todo momento la operación
verificarImpacto() para determinar si el disparo desaparece de la pantalla o impacta con
un enemigo. Como se podrá dar cuenta, para verificar si impacta con un enemigo, esta
operación requiere poder disponer de la lista de enemigos. Es por esta razón que la
operación mantiene una dependencia con ListaEnemigos. Entonces, verificarImpacto()
seguramente tomará cada disparo del Gestor de disparos y comparará su posición con
respecto a la posición de cada enemigo de la lista de enemigos, en cuyo caso en principio
eliminará al enemigo de su lista y el disparo también desaparecerá del gestor.

- Observe que Nave posee una operación validarImpacto(). Esta operación se encarga de
determinar si la nave choca con un enemigo. Por este motivo, se requiere de la lista de
enemigos y de esa manera se establece una dependencia. Nuevamente, este impacto
será confirmado por el hecho de que la posición de la nave coincide con la posición de
un enemigo. Si esto sucede, en principio se disminuirá la cantidad de vidas de la nave y
se eliminará el enemigo de su lista.

Con la información brindada por este ejemplo intente completar el diagrama de clases para que
posea los atributos y operaciones faltantes para validar que sucede si un disparo de los enemigos
impacta con nuestra nave.

#### Como afecta una clase degenerada la relación de dependencia

Si la clase proveedor es una clase “degenerada” no se requerirá definirlo como parámetro en la
operación del cliente. Una clase degenerada es aquella que no posee estado, su función es
brindar un conjunto de operaciones que deberían estar disponibles para todos los objetos.
Muchos lenguajes de programación implementan las clases degeneradas como clases estáticas.

Si bien, las clases estáticas se estudiarán al momento de realizar la programación de clases, se
puede adelantar que su objetivo fundamental es permitir que se puedan utilizar las operaciones
de una clase sin necesidad de crear previamente un objeto de esa clase.

Ejemplo: Con motivo de expresar en un diagrama de clases como afecta la dependencia el uso
de una clase degenerada se propone el siguiente ejemplo: En Java **Math** es un ejemplo de clase
degenerada, por lo cual hay una relación entre la definición de clases degeneradas y las clases
que no poseen atributos (a menos que sean constantes) y sus operaciones son estáticos
(operaciones de clase, que estudiarán posteriormente). Suponga que desea modelar la
dependencia de una clase **Ecuacion** respecto del cálculo de una ecuación cuadrática al aplicar la
clase **Math**

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/0174806f-e42c-4511-add3-f8fb0208feaa)

**Observe que en Math se han definido operaciones de clase (están subrayadas, tal como sucede
con los atributos de clase).**

La operación resolverCuadratica() presenta un tipo de datos de retorno undefined, ya que
ninguno de los tipos de datos UML por defecto se ajusta al hecho de que debe devolver el valor
de 𝑥1y 𝑥2.

#### ¿Pero que es lo que le llama la atención de esta dependencia?

Como habrá notado, la operación no recibe como parámetro un objeto de la clase Math. Esto
se debe al hecho que Math es degenerada, por lo cual no se crean objetos a partir de ella, por
lo cual no hay forma de pasar un objeto como parámetro. Pero al ser degenerada, es posible
utilizar sus operaciones sin ningún problema: pow() permite obtener la potencia de un número,
para lo cual recibe como parámetro el número y el exponente, devolviendo la potencia
generada; mientras que sqrt() devuelve la raíz cuadrada de un número. Si recuerda la ecuación
que permite obtener las raíces de una ecuación cuadrática utilizan ambas operaciones.

# 🟣 SEMANA 06

# INTRODUCCIÓN
La herencia es una propiedad específica del paradigma orientado a objetos. Este pilar constituye
también una relación entre clases. Una relación permite establecer como interactúan las clases.
En el caso de la herencia esta relación establece que una clase declara a otra clase como su
principal, también se dice que una clase (denominada subclase) declara a otra como su
superclase. Esta declaración se denomina herencia porque la subclase adquiere en forma
automática los atributos y operaciones de la superclase. De esta forma la subclase además de
los atributos y operaciones que posee adquiere los atributos y operaciones de la superclase. El
objetivo de este apunte será describir las implicancias de utilizar esta propiedad y su forma de
modelado en UML.

## REPRESENTACIÓN EN EL DIAGRAMA DE CLASES

En el diagrama de clases de UML la herencia posee un elemento de relación propio basado en
una flecha que une la superclase con sus subclases. Sea el siguiente ejemplo
Figura 1. Ejemplo de herencia y tipos de vista de una herencia
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/920cb973-9a1e-4b8c-aaef-1ca25d7b17eb)

Observe que se ha definido la clase Persona, la cual posee 3 atributos y una operación. Luego se
han definido las clases Profesor y Estudiante. En principio la clase Profesor posee 2 atributos y 1
operación, mientras que la clase Estudiante posee 1 atributo y ninguna operación.
Sin embargo, la flecha que sale de cada una de estas clases hacia la clase Persona, indica que se
está estableciendo una relación de herencia: La clase Persona se convierte en una superclase,
mientras que Profesor y Estudiante se convierten en subclases. Como consecuencia, ahora
Profesor posee 5 atributos y 3 operaciones, mientras que Estudiante posee 4 atributos y una
operación.

La forma de la punta de la flecha de la relación de herencia es muy clara: un triángulo sin relleno
que siempre apunta a la superclase.

## VISTAS DE UNA RELACIÓN DE HERENCIA
Observe nuevamente la Figura 1. En ella se describe que existen dos formas de interpretar la
relación de herencia dependiendo del punto de vista desde el cual se analice la relación. Si se
parte desde la superclase hacia las subclases, la relación de herencia describe un proceso de
especialización: esto significa que cada una de las subclases pueden definir atributos y
operaciones que no son comunes entre ellas. Esto permite que cada una de estas subclases 
pueda brindar con mayor detalle sus propias características (atributos) y responsabilidades
(operaciones).
Si, por el contrario, analizamos la relación de herencia desde las subclases hacia la superclase,
estaremos en presencia de un proceso de generalización. Esto es, en la superclase se definirán
los atributos y operaciones que son comunes o “genéricos” a todas las subclases. El proceso de
generalización-especialización de la relación de herencia debería poder brindarle un punto de
referencia para determinar si existe esta relación entre dos clases

## VALIDACIÓN DEL MODELADO DE UNA RELACIÓN DE HERENCIA
En la figura 2, se intenta establecer una relación de herencia entre la clase Casa y la clase Mueble,
donde la primera se convierte en la superclase y la segunda en la subclase. Se ha relacionado
dos clases indicando que Casa es la superclase de Mueble. Si realizamos un análisis del proceso
de generalización – especialización, propuesto para estas clases, podemos detectar que
aparentemente la aplicación de la relación no tiene sentido: un mueble no hereda las cantidades
de habitaciones de una casa, esto es: un mueble no posee como atributo genérico la cantidad
de habitaciones.
Figura 2. Una relación de herencia inválida
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/35781299-5112-402f-a0c8-0c772b3d7dde)

Esto significa que al momento de decidir establecer una relación de herencia entre dos clases se
debe verificar que la misma sea correcta.

## Frase semantica de la herencia

Para ello existe una frase que permite verificar si la relación de herencia que se desea establecer
es correcta. Esta frase se denomina Frase Semántica y en el caso de la herencia es:

`¿<<La subclase>> es un tipo de/es un/es una <<La superclase>>?`

Si la respuesta es afirmativa entonces es correcto establecer la relación de herencia, caso
contrario no se debe establecer la relación de herencia.
En el ejemplo de la figura 2 la frase semántica se aplicaría de la siguiente manera: ¿El mueble es
un tipo de Casa? o ¿El mueble es una casa? Evidentemente la respuesta es NO. Las casas poseen
muebles, pero los muebles no son casas.

De la misma manera para el ejemplo de la figura 1 se puede verificar:
- ¿Un profesor es un tipo de Persona? La respuesta es SI, por lo tanto, fue correcto
establecer la herencia entre ambos
- ¿Un estudiante es un tipo de Persona? En este caso también es correcta la afirmación.

## CONSECUENCIAS DE LA APLICACIÓN DE LA HERENCIA
La herencia conlleva un conjunto de efectos secundarios que se deben tener en cuenta cuando
se decide aplicarla en un modelado de clases.

### Redefinir la visibilidad de los atributos de la superclase
Observe nuevamente la figura 1. Como se había mencionado anteriormente la clase Profesor
hereda 3 atributos de la clase Persona. Sería razonable pensar que la subclase debería poder
manipular directamente esos atributos heredados, como si se hubieran definido dentro de la
misma clase Profesor. Pero esto no sucede. Si bien se creará un único objeto con todos los
atributos y operaciones definidos en Profesor y Persona, las clases diseñadas son diferentes, con
una relación definida pero diferentes al final de cuentas.

Recuerde que la visibilidad privada de los atributos y operaciones (-) indica que ninguna clase
externa puede acceder a esos atributos y operaciones. Por este motivo tanto en UML como en
los lenguajes de programación se ha definido el modificador de acceso protected (protegido o
#) que mantiene la imposibilidad de manipulación de atributos y operaciones de una clase a toda
clase ajena, salvo que sea una subclase. Por lo tanto, en realidad la Figura 1 debería tener la
siguiente forma

Figura 3. Herencia con atributos de la superclase con visibilidad protegida
![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/b237c1c6-1be1-4443-a68a-ac3f2f6e190c)


### La sobreescritura
Es aquella situación donde una misma operación se define tanto en la superclase como en la
subclase. Por ejemplo:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/eaab96bc-ea6d-47aa-9b0b-74cc58521ce4)

Observe que TrianguloIsosceles posee 2 operaciones con el mismo nombre y la misma lista de
parámetros, por lo cual no es una sobrecarga de operaciones.
Formalmente se dice que ambas operaciones tienen la misma semántica (nombre de la
operación) y la misma firma (lista de parámetros de la operación). Este es el único caso en el
cual los lenguajes de programación permiten que un objeto posea dos operaciones iguales.
¿Porque se permite esta situación? En primer lugar, porque no se puede romper la característica
principal de una herencia: la subclase hereda los atributos y operaciones de la superclase.
En segundo lugar, si bien tenemos dos clases diferentes, por la relación de herencia, la
instanciación genera un único objeto. Es decir, cuando un lenguaje de programación crea un
objeto de TrianguloIsosceles, el mismo poseerá 3 atributos y 2 operaciones.
Ante esta situación cabe la pregunta: Si se invoca la operación getPerimetro() ¿Cuál de las dos
operaciones que posee se ejecutará?
Por defecto los lenguajes de programación asumirán que la operación que se ha definido en la
subclase es una “especificación” de la definida en la superclase, por lo tanto, al poseer mayores
detalles la lógica indica que se debe ejecutar, obviando de esta manera, la operación definida
en la superclase. Este proceso se conoce como sobreescritura. Esto significa que existen ambas
operaciones en la subclase pero que al momento de invocar el nombre de la operación se
ejecutará la de la subclase, porque sobre escribe o redefine la de la superclase; dando el efecto
o impresión de que la subclase solo posee el método definido en la subclase.

Formalmente los lenguajes de programación seguirán los siguientes criterios coherentes con la
definición de herencia y sus procesos de especialización y generalización:

- Si se crean objetos de la subclase, la operación que se ejecutará será la definida en la
subclase, ya que el proceso de especialización asume que esta operación redefine o
sobreescribe la de la superclase.

- Si se crean objetos de la superclase, la operación que se ejecutará será la definida en
esta, ya que el concepto de generalización supone que la superclase no conoce los
atributos y operaciones de las subclases. En esto caso no se aplica la sobreescritura.
La sobre escritura supone un conjunto de beneficios:

- Es posible crear una nueva forma de ejecutar una operación sin necesidad de
modificarla o eliminarla. Se redefine su funcionamiento en la subclase sin afectar la
existente en la superclase. Esto facilita el mantenimiento del código. Lo único que se
debe hacer es cambiar la instanciación de la superclase por la de la subclase.

- Dado que la subclase hereda todos los atributos y operaciones de la superclase, no
debería ocurrir ningún error de integración de la subclase en el sistema, logrando de
esta manera mantener la integridad del sistema a la vez que se optimiza la funcionalidad
(y obviamente se podría agregar nueva funcionalidad en la subclase).

- Las operaciones redefinidas en una subclase pueden invocar la funcionalidad de la
operación sobrescrita definida en la superclase. Es común que la propia operación de la
subclase reutilice la funcionalidad de la operación sobrescrita en superclase para luego
agregar una funcionalidad específica, con lo cual se estima que se disminuye el tiempo
de desarrollo y se promueve la reutilización de funcionalidad.

Puede observar todos estos beneficios en acción en el video “programación de los beneficios de
la sobrescritura”.

### Clases abstractas

Debido a la herencia se establecen relaciones jerárquicas entre clases. Puede suceder que una
superclase sea tan genérica que no tenga sentido instanciarla. En estos casos, se asume que la
superclase posee un alto nivel de abstracción, lo cual provocará que no sea posible definir
algunos o todos sus atributos ya que corresponden a alguna de sus subclases. Misma situación
puede llegar a presentarse en las operaciones de esa clase. En este tipo de situaciones es
conveniente definir clases abstractas. Una clase abstracta es aquella que por definición no se
puede instanciar. Desde el punto de vista conceptual una clase abstracta es aquella que no
permite una clase que esté más alta en la jerarquía de relaciones, por lo tanto, no podrá heredar
de otra clase definida por el desarrollador. Observe como se modela una clase abstracta en el
diagrama de clases:

Figura 5. Modelado de una clase abstracta

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/12e32ecf-2963-4940-b7b2-207251ca15d7)

Suponga que se crea un objeto de la clase Figura que se observa en la figura 5 y luego se invoca
la operación obtenerPerimetro().
¿Cómo se determinaría cual de todas las posibles ecuaciones para obtener el perímetro de una
figura se utilizaría?

Estamos ante una situación en la cual el desarrollador no puede determinar la ecuación que
debe programar para obtener su perímetro. Esto sucede porque Figura representa a todas las
figuras geométricas, por lo cual crear un objeto de este tipo significaría cometer un error en el
diseño del diagrama de clases.

En estos casos lo que se espera es que se generen objetos de las subclases únicamente. En el
ejemplo de la figura 5, esto representaría crear objetos de la clase Triangulo o Cuadrado, ya que
para estos objetos está establecida la forma en que obtienen sus respectivos perímetros.

Así, cuando no es posible crear un objeto de una clase, se dice que esa clase es abstracta. En
un diagrama de clases una clase abstracta se identifica con el nombre de la clase en cursiva (tal
como está representado en la figura 5, Figura es una clase abstracta).
Observe además que en esta clase abstracta se ha definido una operación que también está en
cursiva. ¿Será una operación abstracta? Exactamente esta operación es abstracta.


#### ¿Qué es una operación abstracta? 

Es una operación que únicamente define su interfaz, pero no
su implementación. La interfaz de una operación incluye el nombre, la lista de parámetros y el
tipo de retorno de una operación. La interfaz es lo que utiliza el protocolo de mensajes para
poder invocar operaciones. La implementación de una operación es el algoritmo que ejecuta la
acción de la operación. Entonces, esto significa que una operación abstracta no definirá su
algoritmo.

¿Entonces quien implementará ese algoritmo? Evidentemente lo implementarán sus subclases
a través de la sobreescritura de las operaciones.

Esto proporciona una manera elegante de diseñar clases y facilitar su programación ya que:

1) Es posible indicar que una operación en la superclase no posee implementación (Por
ejemplo, en Figura la operación obtenerPerimetro()).
2) Cuando se define una operación abstracta SE OBLIGA a que las subclases sobreescriban
esa operación y la implementen. Esto genera lo que se denomina un contrato entre la
superclase y la subclase por la cual la superclase encomienda a la subclase a
implementar la operación definida como abstracta.

Nota importante: una clase abstracta no se puede instanciar, pero puede poseer operaciones
comunes (no abstractas) y atributos

## TIPOS DE HERENCIA

La herencia es simple cuando una subclase hereda únicamente de una superclase. Por el
contrario, una herencia es múltiple si la subclase hereda de varias 2 o más superclases.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/d6099472-3cd1-4fc5-883d-a009a215ea74)
Figura 6. Tipos de Herencia

En la figura 6 se puede observar que Class1 hereda únicamente de Class, por lo cual estamos
ante una herencia simple. En cambio, Class2 hereda a la misma vez de Class y Class3, lo cual
significa que estamos ante una herencia múltiple.

## LA HERENCIA EN LOS VIDEOJUEGOS

En el paradigma orientado a objetos, si bien es posible que el desarrollador cree clases donde
se requiera la herencia, estas siempre convenientemente heredarán de **GameObject**. Esto se
debe a que al menos dispondrán de un atributo que represente la posición del objeto y una
operación para renderizarlo (dibujar, redibujar pintar o refrescar).

Entonces sería conveniente crear una estructura similar a la siguiente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/b4d67a74-7278-4758-8277-1ceae90d645e)
Figura 7. Esquema general de modelado de GameObjects

Como se puede observar, la figura 7 representa un esquema genérico donde todos los
personajes del juego (MainCharacter y Enemie) así como sus recursos (PowerUp) son subclases
de una clase abstracta (GameObject) que posee un atributo position y una operación abstracta
(display()). Esta operación es sobrescrita por la implementación correspondiente a cada
subclase, lo cual permitirá renderizar el objeto en virtud de su posición.

Podría pensar en una jerarquía donde los gameobjects dinámicos puedan ser subclases
GameObject e incorporen una operación move(). De esta clase a su vez heredarían
MainCharacter y Enemie; mientras que PowerUp directamente heredaría de GameObject
debido a que no se mueve.

La complejidad de la jerarquía la definirá Ud. como diseñador.

## git
## INTRODUCCIÓN
En esta sección estudiaremos el funcionamiento de Git y diferentes criterios para realizar un
correcto control de versiones.
Git es un software de control de versiones diseñado por Linus Torvalds. Fue pensado para que
el mantenimiento de versiones de aplicaciones (cuando tienen un gran número de archivos de
código fuente) sea eficiente y confiable. Su propósito es llevar registro de los cambios en
archivos de computadora y coordinar el trabajo que varias personas realizan sobre archivos
compartidos.

## ¿QUÉ ES UN SISTEMA DE CONTROL DE VERSIONES?

Imaginemos que comenzamos un nuevo proyecto que consiste en solo un archivo fuente. Lo
más probable es que se puedan deshacer los cambios que se hicieron durante esa jornada.
Al día siguiente, se continúa con el desarrollo y se mejora el archivo, pero, en el intento, el
programa comienza a presentar errores. Necesitamos volver a una versión anterior del
proyecto, donde no existía el error. Sin embargo, al no contar con un Control de Versiones, no
contamos con respaldo de las versiones previas.

Se denomina Control de Versiones a la gestión de los diversos cambios que se realizan sobre los
elementos de algún producto o una configuración de este. Una versión, revisión o edición de un
producto, es el estado en el que se encuentra el mismo en un momento dado de su desarrollo
o modificación.

## ¿QUE ES EL TRABAJO COLABORATIVO?

Es un modelo de desarrollo basado en la disponibilidad pública del código y la comunicación vía
Internet. Este modelo se hizo popular a raíz de su uso para el desarrollo de Linux en 1991.
Tomando como contexto a Git, podríamos decir que el desarrollo colaborativo proporciona
herramientas para que un gran número de individuos puedan hacer desarrollos en conjunto de
una manera más fácil, menos propensa a errores y rápida de implementar.

## ¿CÓMO FUNCIONA GIT?: El CONCEPTO DE GRAFO Y UNA BREVE DESCRIPCIÓN DE LA TEORIA DE GRAFOS

Anteriormente se ha comentado que un software de VCS es una implementación de una
especificación para realizar control de versiones. Existen diversas especificaciones. Una de ellas,
concretamente la que adopta el software Git está basada en el concepto del grafo.

En matemáticas y ciencias de la computación, un grafo (del griego grafos: dibujo, imagen) es un
conjunto de objetos llamados vértices o nodos unidos por enlaces llamados aristas o arcos que
permiten representar relaciones binarias entre elementos de un conjunto. Son el objeto de
estudio de la Teoría de Grafos.

Un grafo se representa gráficamente como un conjunto de puntos (vértices o nodos) unidos por
líneas (aristas). Desde un punto de vista práctico, los grafos permiten estudiar las interrelaciones
entre unidades que interactúan unas con otras.

Por ejemplo: una red de computadoras puede representarse y estudiarse mediante un grafo, en
el que los vértices representan terminales y las aristas representan conexiones (las cuales, a su
vez, pueden ser cables o conexiones inalámbricas). 

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/98eb3851-2277-4cf8-add3-34f1ae7cc17e)

Un grafo está compuesto por:

- Aristas: son las líneas con las que se unen los vértices de un grafo.
- Aristas adyacentes: 2 aristas son adyacentes si convergen en el mismo vértice.
- Aristas paralelas: son dos aristas conjuntas si el vértice inicial y final son el mismo.
- Arista cíclica: es la arista que parte de un vértice para entrar en sí mismo.
- Cruce: son 2 aristas que cruzan en un mismo punto.
- Vértices: son los elementos que forman un grafo. Cada uno lleva asociada una valencia
característica según la situación, que se corresponde con la cantidad de aristas que
confluyen en dicho vértice.
- Camino: se denomina camino de un grafo a un conjunto de vértices interconectados por
aristas. Dos vértices están conectados si hay un camino entre ellos

**Git no piensa ni almacena sus datos de esta manera. Git considera sus datos como un conjunto
de snapshots (instantáneas) de un mini sistema de archivos. Git maneja sus datos como una
secuencia de copias instantáneas.**

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/e8929f7c-5055-45bb-abac-00547982e657)

## ESTADOS Y SECCIONES DE UN REPOSITORIO GIT

Esto es lo más importante que debes recordar acerca de Git si quieres que el resto de tu proceso
de aprendizaje prosiga sin problemas. Git tiene tres estados principales en los que se pueden
encontrar tus archivos: confirmado (committed), modificado (modified), y preparado (staged).
1) Confirmado (Commited): significa que los datos están almacenados de manera segura
en tu base de datos local.
2) Modificado (Modified): significa que has modificado el archivo pero todavía no lo has
confirmado a tu base de datos.
3) Preparado (Staged): significa que has marcado un archivo modificado en su versión
actual para que vaya en tu próxima confirmación.

Esto nos lleva a las tres secciones principales de un proyecto de Git: El directorio de Git (.git
directory), el directorio de trabajo (working directory), y el área de preparación (staging area):

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/e89c15fa-5dbd-4791-b570-3d0f2bb835a0)


El directorio de Git es donde se almacenan los metadatos y la base de datos de objetos para tu
proyecto. Es la parte más importante de Git, y es lo que se copia cuando clonas un repositorio
desde otra computadora.
El directorio de trabajo es una copia de una versión del proyecto. Estos archivos se obtienen de
la base de datos comprimida en el directorio de Git (haciendo un Checkout the Project), y se
colocan en disco para que los puedas usar o modificar.
El área de preparación es un archivo, generalmente contenido en tu directorio de Git, que
almacena información acerca de lo que va a ir en tu próxima confirmación. A veces se le
denomina índice (“index”), pero se está convirtiendo en estándar el referirse a ella como el área
de preparación.

El flujo de trabajo básico en Git es algo así:
1) Modificas una serie de archivos en tu directorio de trabajo.
2) Preparas los archivos, añadiéndolos a tu área de preparación.
3) Confirmas los cambios, lo que toma los archivos tal y como están en el área de
preparación y almacena esa copia instantánea de manera permanente en tu directorio
de Git.

Lo anterior esquemáticamente se representa de la siguiente manera:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/25043140-1fc7-4f01-9fed-983416309f54)

Donde se observa que el pasaje de un estado a otro se realiza a través de comandos de Git. De
manera resumida para pasar del working directory al stagig area se utiliza el comando git add,
mientras que para pasar de esta última área al .git directory hay que realizar un git commit.
Si una versión concreta de un archivo está en el directorio de Git, se considera confirmada
(committed). Si ha sufrido cambios desde que se obtuvo del repositorio, pero ha sido añadida al
área de preparación, está preparada (staged). Y si ha sufrido cambios desde que se obtuvo del
repositorio, pero no se ha preparado, está modificada (modified).

## GIT STATUS
Tomando como referencia el ejemplo de proyecto sobre el que se ha realizado el seguimiento
mediante git init, podemos verificar que, aunque posee el archivo .pde que Processing crea
dentro del directorio, este resultará desde el punto de vista de Git como un nuevo elemento
dentro del proyecto. Esto lo comprobaremos al ingresar el siguiente comando.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/80bf3907-5634-4f6f-84ee-fccac34d8109)

El comando nos brinda mucha información:

1) En primer lugar, nos indica que estamos parados en la Rama Principal, es decir el camino
que por defecto Git realiza el seguimiento.
2) En segundo lugar, nos indica que no hemos realizado ninguna confirmación (commit).
Los commits permiten confirmar los cambios realizados cuando los pasamos desde el
staging area al .git drectory o repositorio. En este ejemplo es natural, porque recién
hemos creado el directorio.
3) En tercer lugar, nos informa que ha detectado archivos que no se están siguiendo
(untracked files). Es decir, se han creado nuevos archivos, o aquellos existentes
presentan modificaciones con respecto a la versión almacenada en el directorio de git.
Para este ejemplo, significa que HolaMundoProcessing.pde está en el estado (modified),
o lo que es lo mismo se halla en el working directory. Esto se debe a que Git observa que
hay un archivo en el working directory del cual no encuentra una versión anterior
(instantánea o snapshot) en el .git directory. Por lo tanto, Git no lo va a incluir hasta
que se lo indiquemos explícitamente.

A su vez, brinda información sobre como poder colocar este cambio en el staging area mediante
el comando git add. Esquemáticamente podemos visualizar esta situación de la siguiente
manera:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/54797494-1d46-47b7-b182-5ca61822c66f)

## GIT ADD

Se utiliza para comenzar a rastrear un archivo; por ejemplo puedes ejecutar lo siguiente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/b9f7f736-35d9-4fdd-871c-0f83488d49bc)

Puede observar, además, que luego de ejecutar el comando, una nueva consulta de estados nos
informa que existen cambios a ser confirmados. Específicamente el cambio radica en que existe
un nuevo archivo a seguir (new file: HolaMundoProcessing.pde).
Esto significa que el comando add ha cambiado el estado del archivo, pasándolo de modified a
staged:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/15caa9f9-9575-4b05-be3f-4e44a5b2ad3e)

El comando git add puede recibir tanto una ruta de archivo como de un directorio; si es de un
directorio, el comando añade recursivamente los archivos que están dentro de él.
Si generamos un commit en este punto, la versión del archivo en el momento en que hayamos
ejecutado el comando git add va a permanecer en el snapshot histórico anterior.
Pero si modificamos y guardamos los cambios del archivo.

## GIT COMMIT

Una vez que el/los archivos/directorios se encuentran en el área de preparación (staging area),
estamos listos para confirmar los cambios ejecutando un commit de la siguiente manera:

Sin embargo, vamos a recomendar que se realice un commit con definición de un mensaje, para
lo cual se utiliza la opción -m. Para nuestro ejemplo, usaremos lo siguiente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/147f4d5a-62e2-4f42-829e-2457243e97b5)

Como puede notar se genera una respuesta que indica que se ha agregado al archivo 5 nuevas
líneas y que se han confirmado los cambios.
Específicamente nos brinda información acerca de:
- La rama (branch) donde confirmamos los cambios (main)
- El identificador SHA-1 del commit (6180c2c)
- Cuántos archivos fueron modificados
- Estadísticas acerca de las líneas que fueron insertadas o removidas en el commit.
Cada vez que hagamos un commit estaremos generando una nueva versión del proyecto, o
snapshot, la cual podemos revertir o comparar luego.

## GIT LOG

Antes de continuar viendo otras opciones de git commit, resulta conveniente estudiar el
comando git log. Luego de haber creado varios commits, o mismo si hemos clonado un
repositorio con un historial de commits existente, probablemente queramos mirar hacia atrás
para ver qué ha pasado en el repositorio. Con el comando git log logramos esto:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/e94e0015-4965-443a-a656-eebb2c954664)

Por defecto, sin parámetros, git log lista los commits hechos en un repositorio en orden
cronológico inverso; esto es, el commit más reciente se verá primero. Como podemos ver, este
comando enumera cada commit con su identificador SHA-1, el nombre de autor e email, la fecha
de escritura y el mensaje del commit. 

Este comando viene con muchos atajos y parámetros que podemos agregar para que la salida
en la línea de comandos no sea tan abundante. Particularmente las opciones de --oneline y --
graph son sumamente útiles respectivamente, para mostrar información abreviada sobre cada
commit y para poder ver un gráfico ASCII mostrándonos nuestro historial de commits:

# 🟠 SEMANA 07

## CONCEPTO INTERFACES

En las clases se definen operaciones. Estas operaciones se definen considerando el nombre de
la clase, el nombre de la propia operación, los parámetros que reciben y su valor de retorno.
Estos 3 últimos elementos constituyen “La firma de la operación”.
El conjunto de todas las firmas definidas en una clase (y por consecuencia en el objeto) se
denomina “Interfaz del objeto”. La interfaz de un objeto engloba al conjunto de solicitudes que
se le puede enviar al objeto (Del libro
Design Patterns: Elements of Reusable
Object-Oriented Software).

En criollo lo anterior indica: defina las operaciones disponibles en la clase. Bien…y ahora ¿Cómo
pueden acceder a esas operaciones OTROS objetos?

1) Hay que definir un mecanismo para que esas operaciones estén disponibles (lo que se
denomina Interfaz del objeto).
2) Esa interfaz del objeto es la propia semántica (el nombre del método) y firma de la
operación (el conjunto de parámetros del método); es decir para acceder a la operación
se debe hacer referencia al nombre de la operación, sus parámetros y tipo de retorno.
3) La forma en que un objeto se comunica con la interfaz de otro objeto es a través del
protocolo de mensajes, el cual según nuestro lenguaje de programación (Processing) se
define como: nombreDelObjeto.nombreDelMétodo(parametros);

## REALIZANDO UNA APROXIMACIÓN DESDE LA EXPERIENCIA DEL MODELADO

En la programación orientada a objetos, a veces es útil definir **QUÉ** debe hacer una clase, pero
no **CÓMO** lo hará. Para realizar lo anterior podemos recurrir a dos estructuras:

1) Por un lado, las clases abstractas, las cuales vimos cómo se definen. Estas clases tienen
la particularidad de que en ellas se pueden definir tanto operaciones “normales o
concretas” como las denominadas operaciones abstractas. Al momento de llevar un
diagrama de clases modelado a la etapa de programación, las operaciones concretas
poseen implementación. Es decir, el desarrollador deberá codificar el algoritmo de esa
operación. En cambio, las operaciones abstractas no poseen implementación. Esto
significa que alguna subclase de la clase abstracta deberá proporcionar la
implementación de las operaciones abstractas definidas en la superclase abstracta.
En pocas palabras una clase abstracta puede poseer operaciones abstractas (aquellas
en la que especifica la semántica y la firma, pero no su implementación)
Un ejemplo clásico de la bibliografía es el siguiente

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/7fdd35c9-9c2e-4440-97e6-3ef14a7b4b7d)

Tenemos una superclase abstracta. En esta clase se pueden definir atributos como en
cualquier clase. También posee una operación concreta (mover()), que recibe dos
parámetros para cambiar la posición de la figura en un espacio 2D. La operación
**calcularSuperficie()** es abstracta. Resulta claro que no posee implementación
porque sin saber el tipo de figura no es posible utilizar una “formula” para calcular esta
operación. Se hace necesario definir subclases, y que cada una de ellas sobre escriba
esta operación para establecer la implementación correcta.

2) Si bien las clases y operaciones abstractas son útiles, es posible llevar este concepto un
paso más allá. Tanto en UML como en los principales lenguajes de programación, es
posible separar por completo la interfaz de una clase de su implementación, utilizando
interfaces.

¿Por qué querríamos hacer esto?

Las interfaces sirven para representar “contratos”. Establecen que operaciones deberán
implementar las clases que adhieran a este contrato. De esta manera, si una clase
adhiere a este contrato, debe respetarlo, por ende, deberá implementar el código de
todas las operaciones que están definidas en ese contrato.

¿Y esto para que nos sirve?

Separar la interfaz de su implementación en términos de ingeniería del software implica
minimizar el acoplamiento y maximizar la cohesión. Para no entrar en detalles de estos
dos conceptos, suponga que debe desarrollar una aplicación que ordena una lista de
cualquier tipo objetos. Ud podría crear algo como esto:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/3c44e852-69c4-4620-8543-d1ea10faf323)

Observe varias cosas:
Por empezar se define una interface denominada Comparable. Toda clase que
implemente esta interfaz establece un contrato por el cual esa clase debe tener
implementado una operación **compareTo()** que compara ese objeto contra otro
objeto, devolviendo un valor que indica el resultado de la comparación (por ejemplo
podría ser: negativo, 0 o positivo si el objeto actual es menor, igual o mayor
respectivamente al objeto comparado).
Probablemente si Ud define una clase Persona no piense que deba poseer una
operación **compareTo()** como algo común que se le pediría a una persona. Pero el
contrato establece claramente que debe implementar esa operación. De allí la primera
utilidad de una interface.

En segundo lugar, si observa la clase OrdenacionBurbuja notará que posee un
atributo que es una lista o un arreglo de objetos comparables, y además posee una
operación **ordenarLista()**. Ud. podría agregar otra clase que ordene utilizando
otra técnica de ordenación (por ejemplo, debido a un requisito no funcional, respecto
del tiempo de respuesta del método de ordenación, es decir que se necesita un método
más rápido de ordenación que el de burbuja) sin casi tocar todo el resto del modelo.
También podría agregar nuevos mecanismos de comparación para la persona, lo cual
agrega versatilidad; algo que no posee Factura, ya que solo posee un mecanismo de
comparación, que sería por el monto. Todo gracias a la combinación del uso de
interfaces y clases abstractas.
En tercer lugar, aparece una nueva relación, que es la dependencia. La operación
**compareTo()** no puede llevarse a cabo si no recibe por parámetro un objeto de tipo
Object. Esta relación se utiliza para evitar que una clase deba tener un atributo de
otra clase, así en este caso **Comparable** no está ligado a **Object** (no conoce a
Object, o no tiene referencia a Object, o no apunta a **Object**). Además, como
**Comparable** es una interfaz, por definición no posee atributos.

## SOBRE LA DEFINICIÓN DEL CONTRATO

En este contrato, la interfaz DEFINE:
- Los nombres de las operaciones
- Su tipo de retorno
- El tipo y cantidad de parámetros que reciben las operaciones
En este contrato, la interfaz NO DEFINE:
- Implementaciones (en una interfaz todas las operaciones son abstractas)
- Atributos
Al igual que las clases abstractas, las interfaces no se pueden instanciar.
Generalmente se las confunde con clases abstractas, aunque la diferencia principal reside en
que para que una clase herede de otra abstracta debe seguir cumpliéndose la frase semántica
**“es un tipo de”**, y además las operaciones que se definan tienen un sentido asociado al nombre
de la clase; mientras que una clase puede implementar una o varias interfaces, simplemente con
el objetivo de indicar el contrato de operaciones que debe cumplir.
En adición a lo indicado en el párrafo anterior, mientras que la forma en que se lee la relación
de una clase cualquiera con su clase abstracta es **“es un tipo de”**, en las interfaces la lectura es
**“se comporta como”.**
  
Por último, hay que recordar que las interfaces no son clases

## REPRESENTACIÓN EN UML

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/f810bf6e-6c3e-413c-ae86-94d31a77c160)

Podemos notar varias cosas (que también están reflejadas en el primer ejemplo):
- El estereotipo <<interface>> se antepone al nombre de la interfaz
- Se suele denotar el nombre de la interfaz con la letra I, no siendo obligatorio, pero es
comúnmente aceptado dentro del desarrollo de software. Sobre todo, entre los
programadores.
- El nombre de la operación está en cursiva para resaltar que es abstracto, aunque
algunos autores no lo ponen, por cuanto se sobre entiende al estar definido dentro de
una interface.
- La relación es similar al de la generalización, pero la línea es punteada, y tiene por
nombre realización o implementación.

## OTRAS UTILIDADES DE LAS INTERFACES

Dado que las interfaces permiten definir contratos únicamente sobre el comportamiento de las
clases pueden resultar útiles para resolver de manera elegante problemas de diseño.
Por ejemplo, suponga que crea un videojuego donde utilizará diferentes personajes que son
animales. Suponga que utiliza aves como personajes, aquí sabe que todas las aves comen, pero
no todas las aves vuelan, y justo uno de sus personajes es un pingüino. En términos de diseño,
podrías decidir crear una clase abstracta Ave con el método comer() y luego crear una subclase
AveVoladora y que esta posea el método volar(). Así por ejemplo un Halcon heredará de
AveVoladora, mientras que Pingüino de Ave.
Pero, si reflexiona un poco más, esta decisión se realiza sobre el comportamiento de las aves.
Por lo cual una solución más elegante sería la siguiente:

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/2eb7e92e-96bc-4797-9cdc-3bb5bf43bd89)

Con esto establecemos un contrato únicamente con las aves que son voladoras, o dicho de otra
manera que tienen comportamiento de voladoras.

## CONCEPTO DE POLIMORFISMO
## Introducción

El polimorfismo es una propiedad del paradigma de objetos, en este caso la última que estamos
estudiando (las anteriores fueron abstracción, encapsulación y la herencia). Esta propiedad permite
trabajar de manera general, en lugar de trabajar de manera específica. Trabajar de manera general
permite facilitar la tarea de escalabilidad de la aplicación orientada a objetos. La escalabilidad hace
referencia a la posibilidad de poder ir aumentando la complejidad y los servicios que provee la
aplicación.

El tipo de polimorfismo que estudiaremos será el polimorfismo limitado. Este tipo de polimorfismo
requiere de la presencia previa de la herencia simple. La herencia simple implica que una clase solo
puede heredar a lo sumo de una única otra clase.
Esta particularidad nos permitirá escribir programas que procesan objetos que compartan la misma
superclase (ya sea de manera directa o indirecta [esto es usar interfaces]) como si todos fueran
objetos de la superclase. Suponga que crea una aplicación que deba simular el movimiento de
varios tipos de animales para un juego con vista desde arriba. En este tipo de juegos el movimiento
será en dos dimensiones. Las clases Pez, Rana y Ave representan los tipos de animales que se
están evaluando programar. 
Además estas clases heredan de la clase Animal, la cual contiene una
operación denominada mover() que a su vez devuelve la posición actual del animal luego de realizar
el movimiento (esto es los valores x e y de una plano). Como puede imaginar cada tipo de animal
se mueve de manera diferente, entonces lo más conveniente sería que cada uno de ellos sobre
escriba la operación mover, lo cual en términos del diagrama de clases sería equivalente a

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/a45a10a7-5de5-4158-b2a7-7b264adaa692)

Entonces podemos afirmar que no solamente se requiere la herencia simple, sino que además debe
usarse la sobreescritura de las operaciones para poder aplicar el polimorfismo. Llegado a este
punto, ¿qué es el polimorfismo?

Suponga que el programa mantiene un arreglo de tipo Animal, donde cada una de las referencias
de este tipo corresponden a alguna de las subclases. Entonces para simular el movimiento de cada
animal, a cada elemento del arreglo se le envía el “mismo mensaje”, es decir se invoca la operación
mover() del objeto de tipo Animal. Pero por la sobreescritura, el resultado al “mismo mensaje” 
penderá de la implementación que se realizó en la operación realizada en cada clase en
particular. Esta capacidad para responder a un mismo mensaje de manera diferente que poseen los
objetos se denomina polimorfismo, específicamente polimorfismo limitado, el cual
esquemáticamente para este ejemplo en particular estaría representado de la siguiente manera:


![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/b8886815-99e9-4083-bd4c-031c83298f75)

Con este esquema se puede confiar en que cada objeto sabrá como “hacer lo correcto” (es decir,
lo apropiado para ese tipo de objeto) respecto de la manera en que debe realizar la operación
mover() de manera independiente a los otros tipos de animales.
En este esquema, observe que en este tipo de polimorfismo el efecto polimórfico es disparado por
un método que recibe en dependencia un objeto de la superclase, desde el cual se invoca el método
sobreescrito. Esto significa que para obtener el resultado de las “muchas formas diferentes” que
adquiere un mismo mensaje (en este aso simularMovimeintoAnimal) la superclase debe ser
instanciada por medio de alguna de sus subclases, ya que de no ser así sería imposible que se
manifieste la sobreescritura.

De manera formal, el polimorfismo es la propiedad del paradigma orientado a objetos que posibilita
que un objeto responda de diferente manera a un mismo mensaje. Específicamente, el
polimorfismo limitado es aquel en el que el comportamiento polimórfico se obtiene al instanciar
un objeto de una clase a partir de una de sus subclases, de tal manera que la sobreescritura genera
el efecto de una respuesta diferente al mismo mensaje.

## Ventajas estructurales del polimorfismo

Gracias a polimorfismo es posible extender con facilidad los requerimientos de la aplicación
(escalabilidad): pueden agregarse nuevas clases con solo modificar un poco (o nada) las porciones
generales del programa, siempre y cuando las nuevas clases sean parte de la jerarquía de herencia
que el programa procesa en forma genérica.

Observe los videos “La lógica del polimorfismo explicada con Minecraft y ”La mejor técnica para
programar videojuegos sin perder el tiempo: polimorfismo. Luego realice en grupo la actividad
solicitada.




