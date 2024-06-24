# Glosario

Definiciones de un conjunto de términos usados a través de este jupyter book para mejorar la comprensión de los mismos.

```{glossary} 
{term}`Booleano`
  <div align="justify">Este representa los valores: True (verdadero) o False (falso). Los booleanos son utilizados en expresiones lógicas y en la toma de decisiones en estructuras de control de flujo, como declaraciones if, bucles while y for, entre otros. Este tipo de dato también son inmutables. Esto significa que, una vez que se ha asignado un valor booleano, no se puede modificar directamente. Aunque su inmutabilidad impide cambios directos.</div>
  
{term}`Bucle`
   <div align="justify">Son una herramienta para alterar el flujo normal de un programa. Nos permiten repetir una porción de código tantas veces como queramos. Python incluye únicamente dos tipos de bucle: while y for.</div>
  
{term}`Ciclo For`
  <div align="justify">Es una estructura de control que permite iterar sobre una secuencia (como una lista, tupla, cadena de texto, o cualquier iterable). Se define con la palabra clave `for`, seguida de una variable de iteración, la palabra clave `in`, y la secuencia sobre la cual iterar. Durante cada iteración, la variable de iteración toma el valor de cada elemento de la secuencia, permitiendo ejecutar un bloque de código repetidamente para cada elemento. Son fundamentales para procesar colecciones de datos de manera eficiente en Python.</div>

{term}`Concatenar`
  <div align="justify">Es agregar o unir el valor de una cadena a otra cadena. En python por ejemplo usando el signo + o a través del método join().</div>
  
{term}`Data Frame (DF)`
  <div align="justify">En el contexto de la programación y análisis de datos se refiere a una estructura de datos bidimensional que se utiliza para almacenar y manipular datos tabulares, similar a una hoja de cálculo o una tabla de base de datos.</div>
  
{term}`Diccionario`
  <div align="justify">Un diccionario  es una colección de datos desordenada de pares clave-valor, donde cada clave es única y se utiliza para acceder a su valor correspondiente. Se define usando llaves `{}` y permite una búsqueda rápida, modificación y eliminación de elementos. Los diccionarios son ideales para representar asociaciones y estructuras de datos complejas.</div>

{term}`Entorno de Desarrollo Integrado`
   <div align="justify">Un Entorno de Desarrollo Integrado (IDE, por sus siglas en inglés) es una aplicación de software que proporciona un conjunto completo de herramientas y facilidades, con el objetivo de facilitar el proceso de programación. Un IDE típicamente incluye un editor de código fuente, herramientas de construcción automática, un depurador, y a menudo, un intérprete o compilador. Ejemplos populares son Visual Studio, Eclipse, IntelliJ IDEA y PyCharm.</div>

{term}`Float`
   <div align="justify">Este tipo de dato se utiliza para representar números de punto flotante, es decir, números que pueden tener una parte fraccionaria o decimal. Al igual que los strings y los enteros, los flotantes en Python son también un tipo de dato inmutable, lo que significa que una vez que se crea un número, no se puede modificar directamente.</div>
 
{term}`Funciones`
    <div align="justify">Son bloques de código reutilizable que realizan una tarea específica cuando son llamadas. Se definen con la palabra clave `def`, seguida del nombre de la función y paréntesis que pueden contener parámetros opcionales. Las funciones pueden devolver valores usando la palabra clave `return` y pueden acceder a variables definidas dentro o fuera de ellas, dependiendo del ámbito de estas variables.</div>
  
{term}`Integer`
   <div align="justify">El tipo de dato Int representa números enteros, es decir, números sin parte fraccionaria o decimal. Los enteros pueden ser positivos, negativos o cero. Al igual que los strings, los enteros son también un tipo de dato inmutable, lo que significa que una vez que se crea un número, no se puede modificar directamente. Sin embargo, se pueden realizar diversas operaciones matemáticas y crear nuevos números en base a los existentes. Este tipo de inmutabilidad implica que, en lugar de modificar el valor existente, se crean nuevos valores numéricos con las operaciones correspondientes.</div>

{term}`Iterar o Iteraciones`
   <div align="justify">Significa realizar una acción varias veces. Cada vez que se repite se denomina iteración.Los bucles sirven para que los programas implementen iteraciones, es decir, ejecuten un mismo bloque de código dos o más veces mientras se cumple la condición declarada. Cuando la condición llega a ser falsa, el programa sale del bucle y continúa con su ejecución de forma secuencial.</div>

{term}`Lenguaje de Programación`
   <div align="justify">Un lenguaje de programación es un sistema formal compuesto por un conjunto de reglas y símbolos que permite a los desarrolladores escribir programas que serán ejecutados por una computadora. Estos lenguajes son utilizados para expresar algoritmos y realizar tareas específicas, como manipular datos, controlar dispositivos hardware, o crear aplicaciones completas. Ejemplos de lenguajes de programación populares incluyen Python, Java, C++, JavaScript, y Ruby.</div>

{term}`Librerías (Libraries)`
   <div align="justify">Son colecciones de código y funciones preescritos que amplían las capacidades del lenguaje de programación Python. Proporcionan una amplia gama de herramientas y módulos para diversas tareas, lo que facilita a los desarrolladores trabajar en tareas específicas sin tener que reinventar la rueda.</div>

{term}`Lista`
   <div align="justify">En Python es una colección ordenada y mutable de elementos, definidos entre corchetes `[]` y separados por comas. Puede contener diferentes tipos de datos y permite operaciones como indexación, adición, eliminación y modificación de elementos. Las listas son versátiles y ampliamente utilizadas para almacenar secuencias de datos.</div>

{term}`Jupyter Notebook`
    <div align="justify">Es una aplicación web que permite crear y compartir documentos interactivos que contienen código, visualizaciones y texto explicativo. Es ampliamente utilizado en ciencia de datos, aprendizaje automático y análisis exploratorio de datos. Soporta múltiples lenguajes de programación, siendo Python el más común. Jupyter facilita la integración de código ejecutable, gráficos y narrativa en un solo documento, promoviendo una colaboración y presentación efectivas.</div>
    
{term}`Métodos`
    <div align="justify"> En Python, son funciones definidas dentro de la definición de una clase. Estos métodos son acciones que un objeto de esa clase puede realizar. Los métodos pueden acceder y manipular los datos que pertenecen al objeto.</div> 

{term}`Operadores`
    <div align="justify"> En Python, los operadores son símbolos especiales que permiten realizar operaciones entre valores y variables. Hay varios tipos de operadores: Aritméticos (`+`, `-`, `*`, `/`,), Operadores de Asignación (`=`, `+=`, `-=`, `*=`) y de Comparación (`==`, `!=`, `<`, `>`, `<=`, `>=`). Estos operadores son esenciales para la manipulación y evaluación de datos en Python, permitiendo realizar desde cálculos simples hasta decisiones condicionales en programas más complejos..</div>  
    
{term}`Python`
   <div align="justify">Python es un lenguaje de programación de alto nivel, interpretado y de propósito general, conocido por su legibilidad y simplicidad sintáctica, lo que facilita el aprendizaje y la escritura de código. Fue creado por Guido van Rossum y lanzado por primera vez en 1991. Python soporta múltiples paradigmas de programación, incluyendo programación procedimental, orientada a objetos y funcional. Sus características incluyen una extensa biblioteca estándar, gestión automática de memoria, y una sintaxis que permite a los desarrolladores expresar conceptos en menos líneas de código en comparación con otros lenguajes como C++ o Java. Python es ampliamente utilizado en diversos campos como desarrollo web, ciencia de datos, inteligencia artificial, automatización de tareas, y más.</div>

{term}`Rstudio`
   <div align="justify">RStudio es un entorno de desarrollo integrado (IDE) para el lenguaje de programación R, utilizado principalmente para análisis estadístico y visualización de datos. Ofrece una interfaz amigable que incluye un editor de código, un visor de gráficos, herramientas de depuración y gestión de paquetes. RStudio facilita la creación de scripts, el manejo de datos y la generación de informes reproducibles. Es ampliamente utilizado en la comunidad de ciencia de datos y está disponible en versiones de escritorio y servidor.</div>
    
{term}`String(cadena de texto)`
    <div align="justify">Es una secuencia de caracteres encerrados entre comillas simples (`'`) o dobles (`"`). Los strings son objetos inmutables, lo que significa que no pueden modificarse una vez creados, aunque se pueden crear nuevas cadenas combinando o modificando otras. Python proporciona una amplia gama de métodos integrados para manipular strings, como la concatenación, división, búsqueda de subcadenas y formateo. Los strings son fundamentales en Python para la manipulación de texto y la representación de datos en muchos contextos, como el procesamiento de archivos, la interfaz de usuario y la comunicación de datos.</div>

{term}`Tupla`
  <div align="justify">En Python es una colección ordenada e inmutable de elementos, definidos entre paréntesis `()`. Puede contener diferentes tipos de datos y permite acceder a sus elementos mediante indexación. Las tuplas son útiles para almacenar datos que no deben cambiar a lo largo del tiempo.</div>

{term}`Types (Tipos)`
    <div align="justify">En Python, un "type" (tipo) define la naturaleza de un valor y determina qué operaciones se pueden realizar sobre él. Los tipos básicos incluyen enteros (int), flotantes (float), cadenas de texto (str), listas (list), tuplas (tuple), diccionarios (dict), y conjuntos (set). Cada tipo tiene sus propias propiedades y métodos asociados.</div>

{term}`Values(Valores)`
    <div align="justify">En Python, un "value" (valor) es cualquier dato que una variable puede almacenar y manipular. Los valores pueden ser de diferentes tipos, como números (enteros y flotantes), cadenas de texto, listas, tuplas, diccionarios, conjuntos y más. Los valores pueden ser constantes o cambiantes, y se utilizan en expresiones, operaciones y funciones para realizar cálculos y manipular datos.</div>

{term}`Variables`
    <div align="justify">Las variables son nombres dados a los datos que necesitamos almacenar y manipular en nuestros programas.</div>
    
    

```
