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

### 🧠🧠 LOS ELEMENTOS CENTRALES DE LA ABSTRACCIÓN DE OBJETOS

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

### 📏📏 **Nomenclatura para la Definición de Nombres de Clases**

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

## 📚 **Definición de Operaciones**

Las operaciones representan acciones que pueden ser realizadas por los objetos creados a partir de una clase. La nomenclatura para la definición de operaciones en esta materia sigue las convenciones del lenguaje Java:

1. Las operaciones deben ser verbos en infinitivo.
2. Se escriben en minúscula.
3. No se admiten espacios en los nombres de las operaciones. En la fase de análisis del Diagrama de Clases, se admite el uso de guion bajo (_), pero en la fase de diseño se seguirá la convención de que la primera letra de cada palabra subsiguiente esté en mayúscula.

En un diagrama de clases, las operaciones se definen siguiendo la sintaxis:

\[visibilidad\] nombre ([lista de parámetros])[:tipo de retorno]

Los corchetes indican que estos elementos son opcionales, por lo que solo el nombre de la operación es requerido.
