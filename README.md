# Taller de Python - Procesamiento de Datos a Gran Escala

Este repositorio contiene el desarrollo del **Taller de Python** correspondiente a la asignatura **Procesamiento de Datos a Gran Escala**.

El objetivo principal del taller fue repasar y aplicar los fundamentos de programación en Python por medio de diferentes cuadernos de Jupyter Notebook, trabajando desde conceptos básicos como cadenas y listas hasta temas como funciones, ciclos, condicionales y programación orientada a objetos.

## Autor

**Nombre:** Santiago Martínez López
**Documento:** 1027400439
**Asignatura:** Procesamiento de Datos a Gran Escala
**Universidad:** Pontificia Universidad Javeriana

## Contenido del repositorio

El repositorio está compuesto por los siguientes cuadernos:

* `01-Python-Cadenas.ipynb`
* `02-Python-Tuplas.ipynb`
* `03-Python-Listas.ipynb`
* `04-Python-Conjuntos.ipynb`
* `05-Python-Diccionarios.ipynb`
* `06-Python-Condiciones.ipynb`
* `07-Python-Bucles.ipynb`
* `08-Python-Funciones.ipynb`
* `09_Python_Clases.ipynb`
* `Practico_Bono_1.ipynb`

Cada notebook conserva los ejemplos y explicaciones trabajadas en el taller y contiene el desarrollo de los ejercicios correspondientes a cada tema.

## Temas trabajados

### 1. Cadenas

En este cuaderno se trabajó con textos y cadenas de caracteres en Python.

Se practicaron temas como:

* creación de cadenas;
* indexación;
* indexación negativa;
* slicing;
* uso de `stride`;
* concatenación;
* secuencias de escape;
* conversión a mayúsculas;
* búsqueda de información dentro de una cadena;
* reemplazo de texto.

También se utilizaron métodos como:

```python
upper()
find()
replace()
```

Por ejemplo, se trabajó con slicing para obtener únicamente una parte de una cadena y con `stride` para seleccionar caracteres en determinadas posiciones.

### 2. Tuplas

Se trabajó con tuplas como estructuras de datos que permiten almacenar varios elementos.

Los ejercicios permitieron practicar:

* acceso mediante índices;
* uso de `len()`;
* slicing;
* búsqueda de elementos;
* ordenamiento de valores;
* diferencias básicas entre listas y tuplas.

### 3. Listas

En este cuaderno se trabajó con listas y su manipulación.

Se practicaron operaciones como:

* creación de listas;
* acceso por posición;
* slicing;
* concatenación;
* almacenamiento de diferentes tipos de datos;
* recorrido y manipulación de elementos.

### 4. Conjuntos

Se trabajó con conjuntos o `sets`, principalmente para manejar colecciones sin elementos repetidos.

Se realizaron ejercicios relacionados con:

* creación de conjuntos;
* eliminación automática de valores duplicados;
* conversión entre listas y conjuntos;
* unión de conjuntos;
* comparación entre conjuntos;
* validación de subconjuntos.

### 5. Diccionarios

En este notebook se trabajó con estructuras basadas en pares de **llave y valor**.

Se practicó:

* creación de diccionarios;
* acceso a valores mediante una llave;
* consulta de llaves con `keys()`;
* consulta de valores con `values()`;
* almacenamiento de información relacionada dentro de una misma estructura.

### 6. Condiciones

Se utilizaron estructuras condicionales para controlar el flujo de ejecución de un programa.

Los principales temas fueron:

* `if`;
* `else`;
* operadores de comparación;
* operadores lógicos;
* uso de `or`;
* evaluación de diferentes condiciones.

Los ejercicios permitieron observar cómo el programa puede tomar diferentes decisiones dependiendo de los valores almacenados en las variables.

### 7. Bucles

Se trabajó con ciclos para repetir instrucciones automáticamente.

Se utilizaron principalmente:

```python
for
while
```

Con `for` se recorrieron rangos y listas completas.

Con `while` se trabajaron situaciones donde el ciclo debía continuar únicamente mientras se cumpliera una condición determinada.

Por ejemplo, se recorrió una lista de calificaciones hasta encontrar un valor menor a `6`, momento en el cual el ciclo debía detenerse.

### 8. Funciones

En este cuaderno se practicó la creación y utilización de funciones.

Se trabajó con:

* definición de funciones usando `def`;
* parámetros;
* argumentos;
* valores de retorno;
* reutilización de código;
* funciones aplicadas a diferentes tipos de datos.

El uso de funciones permite evitar repetir instrucciones y organizar mejor un programa.

### 9. Clases

En este cuaderno se realizó una introducción a la programación orientada a objetos.

Se trabajó con:

* clases;
* objetos;
* atributos;
* métodos;
* constructores;
* modificación de propiedades de un objeto.

Como actividad final se creó una clase `Elipse`.

Esta clase permite modificar:

* ancho;
* alto;
* color de relleno;
* color del borde.

También se implementó un método para dibujar la elipse utilizando `matplotlib`.

El resultado final de la actividad se muestra gráficamente dentro del notebook.

### 10. Práctico de bono

El práctico adicional permitió aplicar varios conceptos vistos a lo largo de los cuadernos anteriores.

Se desarrollaron ejercicios mediante funciones como:

* `lesser_of_two_evens`
* `animal_crackers`
* `makes_twenty`
* `old_macdonald`
* `master_yoda`
* `has_33`
* `paper_doll`
* `blackjack`

Estos ejercicios combinaron condiciones, manejo de cadenas, listas, ciclos y funciones.

## Ejecución de los notebooks

Todos los cuadernos fueron ejecutados antes de realizar la entrega.

Esto permite observar directamente dentro de los archivos:

* el código utilizado;
* el número de ejecución de cada celda;
* los resultados obtenidos;
* las salidas impresas;
* las pruebas realizadas;
* las gráficas generadas cuando corresponde.

Por ejemplo, en los ejercicios de cadenas se pueden observar resultados como:

```text
12
ABC
correct
YOU ARE WRONG
```

En el cuaderno de bucles se muestran directamente los valores generados por los ciclos `for` y `while`.

En el cuaderno de clases se encuentra además la salida gráfica correspondiente al objeto `Elipse`.

De esta manera, los notebooks no contienen únicamente el código escrito, sino también la evidencia de su ejecución.

## Documentación

Además del desarrollo del código, los cuadernos incluyen:

* identificación del autor;
* explicación de las actividades;
* desarrollo de los ejercicios;
* resultados de ejecución;
* comentarios dentro del código cuando son útiles;
* conclusiones al final de cada notebook.

Las conclusiones resumen brevemente lo aprendido en cada tema.

## Aprendizajes principales

Después de desarrollar el taller pude repasar varios fundamentos importantes de Python.

Principalmente aprendí o reforcé:

* cómo almacenar y manipular información utilizando diferentes estructuras de datos;
* cómo trabajar con cadenas y posiciones;
* cuándo utilizar listas, tuplas, conjuntos o diccionarios;
* cómo tomar decisiones mediante condiciones;
* cómo automatizar tareas repetitivas usando ciclos;
* cómo dividir un programa en funciones;
* cómo reutilizar código;
* cómo crear clases y objetos;
* cómo modificar atributos mediante métodos;
* cómo generar una representación gráfica utilizando `matplotlib`.

El taller también sirvió para entender mejor la forma en que un problema sencillo puede dividirse en pasos y luego convertirse en instrucciones de Python.

## Forma de entrega

La entrega se encuentra organizada completamente dentro de este repositorio.

Cada tema está separado en su propio archivo `.ipynb`, permitiendo revisar de manera independiente:

1. la explicación del tema;
2. los ejemplos;
3. los ejercicios desarrollados;
4. el código utilizado;
5. las salidas obtenidas;
6. las conclusiones.

El repositorio funciona como entrega final del taller y permite consultar directamente todos los cuadernos desde GitHub.
