# PYTHON BÁSICO

---

![imagen-python](/img/imagen-python.webp)

---


## Índice

## Índice

### 1. [Variables y Tipos de Datos](#1-variables-y-tipos-de-datos)
### 2. [Operadores Básicos](#2-operadores-básicos)
### 3. [Estructuras de Control (Condicionales)](#3-estructuras-de-control-condicionales)
### 4. [Bucles (`for` y `while`) en Python](#4-bucles-for-y-while-en-python)
### 5. [Listas y Tuplas](#5-listas-y-tuplas)
### 6. [Diccionarios](#6-Diccionarios)

---

### 1. **Variables y Tipos de Datos**

   - **¿Qué son las variables?** Imagina que las variables son como "etiquetas" que le pones a una caja para saber qué tiene adentro. Puedes guardar números, palabras, verdadero/falso, etc. Y, cuando necesites esa información, solo tienes que usar la etiqueta (nombre de la variable) para obtener lo que guardaste.
   - **Tipos básicos**:
     - **`int`**: Guarda números enteros, como `5`, `10`, `-3`.
     - **`float`**: Guarda números con decimales, como `1.5`, `3.14`.
     - **`str`**: Guarda texto o palabras, como `"Hola"`, `"Python"`.
     - **`bool`**: Guarda valores de verdadero (`True`) o falso (`False`).
   - **Ejemplo**:
     ```python
     edad = 25  # Guarda el número 25
     nombre = "Ana"  # Guarda el texto "Ana"
     altura = 1.75  # Guarda el número decimal 1.75
     es_mayor = True  # Guarda el valor verdadero
     ```
   - **Explicación Simple**: Las variables son cajas con nombre donde guardas cosas que quieres usar más adelante. Cada variable guarda un tipo específico de dato, como números o palabras.

---

### 2. **Operadores Básicos**

   - **¿Qué son los operadores?** Los operadores son los símbolos que usamos para hacer operaciones básicas, como sumar o comparar. Son como los signos que usamos en matemáticas: `+`, `-`, `>`, `==`.
   - **Tipos de Operadores**:
     - **Aritméticos**: `+`, `-`, `*`, `/` para sumar, restar, multiplicar y dividir.
       - Ejemplo: `5 + 3` te da `8`.
     - **Comparación**: `==`, `!=`, `>`, `<`, `>=`, `<=` para ver si dos cosas son iguales, mayores, menores, etc.
       - Ejemplo: `5 > 3` es `True` (verdadero) porque 5 es mayor que 3.
   - **Ejemplo de Uso**:
     ```python
     suma = 5 + 3  # Calcula 5 + 3 y guarda 8 en la variable "suma"
     es_mayor = 5 > 3  # Verifica si 5 es mayor que 3, guarda True en "es_mayor"
     ```
   - **Explicación Simple**: Los operadores nos ayudan a hacer cuentas y a comparar cosas, para que el programa decida si algo es mayor, igual o distinto a otra cosa.

---

### 3. **Estructuras de Control (Condicionales)**

   - **¿Qué son las condicionales?** Las condicionales son como señales de tráfico: si la señal está en verde, avanzas; si está en rojo, te detienes. En programación, con una condicional le dices al programa "Si pasa esto, haz aquello".
   - **Uso Básico de `if`, `else`, y `elif`**:
     - **`if`**: Evalúa si una condición es verdadera. Si es así, hace lo que le dices.
     - **`else`**: Es lo que pasa cuando la condición no se cumple.
     - **`elif`**: Agrega más condiciones si el `if` no es verdadero.
   - **Ejemplo**:
     ```python
     edad = 20
     if edad >= 18:
         print("Eres mayor de edad")  # Si edad es 18 o más, imprime esto
     else:
         print("Eres menor de edad")  # Si no, imprime esto
     ```
   - **Explicación Simple**: Las condicionales son decisiones que toma el programa según las condiciones. Puedes decirle que haga algo solo cuando se cumple cierta condición.

---

### 4. **Bucles (`for` y `while`) en Python**

   - **¿Qué es un bucle?** Un bucle es una forma de repetir cosas automáticamente. Con bucles, no necesitas escribir algo varias veces si el programa puede hacerlo por ti.
   - **Tipos de Bucles**:
     - **`for`**: Recorre una lista o un rango de números y ejecuta el código una vez por cada elemento o número.
       - Ejemplo:
         ```python
         for i in range(3):  # Repite 3 veces (i toma los valores 0, 1, y 2)
             print("Repetición:", i)
         ```
     - **`while`**: Repite el código mientras se cumpla una condición.
       - Ejemplo:
         ```python
         contador = 0
         while contador < 3:  # Repite mientras contador sea menor que 3
             print("Contador:", contador)
             contador += 1  # Suma 1 al contador en cada repetición
         ```
   - **Explicación Simple**: Los bucles permiten que el programa repita algo automáticamente. Con `for`, le dices cuántas veces repetir; con `while`, repite hasta que la condición ya no se cumple.

---

### 5. **Listas y Tuplas**

   - **¿Qué son?** Las listas y las tuplas son como "cajas grandes" que guardan muchas cosas dentro (números, palabras, etc.), en un orden específico.
   - **Diferencia**:
     - **Listas**: Puedes cambiar lo que tiene adentro, agregar o quitar cosas.
     - **Tuplas**: No se pueden cambiar; son "de una vez y para siempre".
   - **Ejemplo de Lista**:
     ```python
     frutas = ["manzana", "banana", "cereza"]
     frutas.append("naranja")  # Añade "naranja" al final de la lista
     ```
   - **Ejemplo de Tupla**:
     ```python
     numeros = (1, 2, 3)  # Tupla que no se puede cambiar
     print(numeros[0])  # Imprime el primer elemento, 1
     ```
   - **Explicación Simple**: Las listas y tuplas son como listas de compras. En una lista puedes agregar o quitar cosas; en una tupla no puedes cambiar nada una vez que está hecha.

---

### 6. **Diccionarios**

   - **¿Qué son los diccionarios?** Son como una agenda telefónica: tienes un "nombre" (clave) y el "número de teléfono" (valor) asociado a ese nombre.
   - **Cómo funcionan**: En lugar de tener solo un número o palabra como en una lista, cada elemento del diccionario tiene una clave que usas para buscar el valor.
   - **Ejemplo**:
     ```python
     persona = {"nombre": "Juan", "edad": 30}  # Diccionario con clave-valor
     print(persona["nombre"])  # Accede al valor de la clave "nombre" e imprime "Juan"
     ```
   - **Explicación Simple**: Los diccionarios son perfectos cuando necesitas buscar cosas con una clave específica, como un número de teléfono usando un nombre. Puedes acceder a los valores con su clave sin tener que revisar todo.

---

Espero que esta explicación sea clara y fácil de seguir. Cada sección está pensada para que entiendas el concepto desde cero, con ejemplos básicos para que veas cómo funciona Python paso a paso.
