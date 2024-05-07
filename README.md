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

##  VIDEO YOUTUBE <img src="https://i.ibb.co/0Y8QBHD/yt.png" alt="yt" border="0" height="20"> <br>

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





