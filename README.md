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

####  Operador Lógico NO

Al aplicar el operador no, lo que hace es negar (asignar el valor opuesto) de a. Por lo tanto, el
resultado de no a, será falso.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/2a89462a-4cef-405e-9494-be942187b0ab)

#### Operador Lógico Y (o conjunción)

El operador Y toma los valores que devuelven las expresiones lógicas a y b; y evalúa el resultado
en conjunto. 
Así, si tanto a como b son verdaderas, el resultado en conjunto será verdadero, caso contrario
devolverá falso

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/9ca9620b-aa5b-43bf-bfb3-f3968d06564f)

#### El Operador Lógico O (o disyunción)

El operador O toma los valores que devuelven las expresiones lógicas a y b; y evalúa el resultado
en conjunto.

![image](https://github.com/AlexUnju/apunteResumenFpoo/assets/142057928/f1dd6f48-aaa1-44b3-846b-82d947932092)











