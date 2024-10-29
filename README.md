# PYTHON BÁSICO



---

### 1. **Variables y Tipos de Datos**  
   - **¿Qué son las variables?** Imagina que las variables son "cajas" donde puedes guardar diferentes tipos de cosas (números, palabras, verdadero/falso).
   - **Ejemplo**:
     ```python
     edad = 25  # Caja llamada edad que guarda el número 25
     nombre = "Ana"  # Caja llamada nombre que guarda el texto "Ana"
     altura = 1.75  # Caja llamada altura que guarda el número decimal 1.75
     es_mayor = True  # Caja llamada es_mayor que guarda el valor de verdadero
     ```
   - **Explicación Simple**: Estas "cajas" guardan información que usaremos en el programa. Solo tienes que darles un nombre y asignarles un valor.

---

### 2. **Operadores Básicos**  
   - **¿Qué son los operadores?** Son como las operaciones de matemáticas que ya conoces: sumar, restar, multiplicar y dividir. Los operadores nos ayudan a hacer cálculos y a comparar cosas.
   - **Ejemplo de Cálculo**:
     ```python
     suma = 5 + 3  # Caja llamada suma que guarda el resultado de 5 más 3, es decir, 8
     ```
   - **Ejemplo de Comparación**:
     ```python
     print(5 > 3)  # Imprime True porque 5 sí es mayor que 3
     print(5 == 3)  # Imprime False porque 5 no es igual a 3
     ```
   - **Explicación Simple**: Los operadores aritméticos nos ayudan a hacer cuentas; los operadores de comparación nos dicen si algo es igual, mayor, menor, etc.

---

### 3. **Estructuras de Control (Condicionales)**  
   - **¿Qué son las condicionales?** Nos ayudan a que el programa decida qué hacer en función de si algo es verdadero o falso. Usa `if` para decirle al programa "Si pasa X, entonces haz esto."
   - **Ejemplo Simple**:
     ```python
     edad = 18
     if edad >= 18:
         print("Eres mayor de edad")  # Si edad es 18 o más, imprime "Eres mayor de edad"
     ```
   - **Explicación Simple**: Si la condición en el `if` es cierta, entonces se ejecuta el código dentro de `if`. Si no, se salta.

---

### 4. **Bucles (`for` y `while`) en Python**  
   - **¿Qué es un bucle?** Es una forma de repetir algo varias veces sin escribirlo muchas veces. 
   - **Bucle `for`**: Recorre una lista o un rango de números.
     ```python
     for i in range(3):  # Repite 3 veces
         print("Iteración:", i)
     ```
   - **Bucle `while`**: Repite mientras una condición sea verdadera.
     ```python
     contador = 0
     while contador < 3:
         print("Contador:", contador)
         contador += 1  # Suma 1 al contador
     ```
   - **Explicación Simple**: Con `for` y `while`, puedes decirle al programa que repita el código hasta que ya no se cumpla la condición. 

---

### 5. **Listas y Tuplas**  
   - **¿Qué son?** Son "listas de cosas". Las listas pueden cambiarse (puedes agregar o quitar cosas); las tuplas no se pueden cambiar.
   - **Ejemplo de Lista**:
     ```python
     frutas = ["manzana", "banana", "cereza"]  # Lista de frutas
     frutas.append("naranja")  # Agrega "naranja" a la lista
     ```
   - **Ejemplo de Tupla**:
     ```python
     numeros = (1, 2, 3)  # Tupla de números que no se puede cambiar
     ```
   - **Explicación Simple**: Las listas y tuplas son como "cajas grandes" que guardan varias cosas al mismo tiempo, en un orden.

---

### 6. **Diccionarios**  
   - **¿Qué son los diccionarios?** Piensa en ellos como una lista de términos y definiciones, pero en lugar de "palabra: definición", tienes "clave: valor".
   - **Ejemplo**:
     ```python
     persona = {"nombre": "Juan", "edad": 30}  # Diccionario con clave "nombre" y "edad"
     print(persona["nombre"])  # Imprime "Juan" porque accede a la clave "nombre"
     ```
   - **Explicación Simple**: Los diccionarios guardan datos en pares. Útil para cosas donde necesitas una "palabra clave" para encontrar el valor exacto.

---

Este documento está simplificado y organizado para que puedas entender cada concepto paso a paso, desde lo más sencillo (variables) hasta lo más complejo (diccionarios).
