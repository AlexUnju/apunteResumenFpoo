## Apuntes de Fundamentos de la Programación Orientado a Objetos
###### _No olvides darle una estrellita a este repositorio :D  -_ <img src="https://i.ibb.co/0nX0bNR/Screenshot-2024-05-07-164050.png" alt="Screenshot-2024-05-07-164050" border="0" height="30em" align="center">
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
- Análisis del problema.
- Diseño del algoritmo.
- Codificación.
- Compilación y ejecución.
- Verificación.
- Depuración.
- Mantenimiento.
- Documentación.

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
| +                 | Suma                             |
| -                 | Resta                            |
| *                 | Multiplicación                   |
| /                 | División                         |
| ** o ^            | Potenciación                     |
| div               | División entera                  |
| mod, %            | Módulo (resto)                   |
| **++**            | **Incremento**                   |
| **--**            | **Decremento**                   | 

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
## Estructuras Selectivas

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



