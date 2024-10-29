# python


### 1. **Diccionarios en Python**
   - **¿Qué es un diccionario?**: Imagina una lista de contactos donde cada persona tiene un número de teléfono. En lugar de solo nombres, el diccionario en Python guarda datos en pares, como "nombre: teléfono". Así tienes una “clave” (nombre) y un “valor” (teléfono) para buscar o cambiar datos rápidamente.

   - **Cómo crear un diccionario**:
     ```python
     # Esto es un diccionario llamado persona
     persona = {
         "nombre": "Ana",
         "edad": 25,
         "ciudad": "Madrid"
     }
     # Ahora si quiero saber el nombre, solo busco la clave "nombre"
     print(persona["nombre"])  # Resultado: Ana
     ```

   - **¿Y si quiero buscar algo que tal vez no esté en el diccionario?**:
     - Usa `.get(clave)` para buscar sin que te dé error si no existe.
       ```python
       print(persona.get("profesión", "Desconocido"))  # Resultado: Desconocido
       ```
   
   - **Listas de cosas en el diccionario**:
     ```python
     print(persona.keys())    # Muestra todas las claves: nombre, edad, ciudad
     print(persona.values())  # Muestra todos los valores: Ana, 25, Madrid
     print(persona.items())   # Muestra cada par clave-valor juntos: ('nombre', 'Ana'), etc.
     ```

   - **Para eliminar algo en el diccionario**:
     ```python
     persona.pop("edad")  # Elimina la clave "edad" y su valor 25
     print(persona)  # Resultado: {'nombre': 'Ana', 'ciudad': 'Madrid'}
     ```

---

### 2. **Bucle `for` en Python**
   - **¿Qué es un bucle `for`?**: Piensa que tienes que hacer algo repetidamente, como saludar a cada persona en una lista de amigos. En lugar de escribir la misma línea una y otra vez, usas `for` para repetirlo automáticamente.
   
   - **Ejemplo simple**:
     ```python
     # Esto imprime los números del 0 al 4 sin que tengas que escribir cada número
     for i in range(5):
         print(i)
     # Resultado:
     # 0
     # 1
     # 2
     # 3
     # 4
     ```

   - **Usando `for` para ver cada cosa en una lista**:
     ```python
     frutas = ["manzana", "banana", "cereza"]
     for fruta in frutas:
         print(fruta)
     # Resultado:
     # manzana
     # banana
     # cereza
     ```

   - **`for` en un diccionario**:
     ```python
     persona = {"nombre": "Ana", "edad": 25, "ciudad": "Madrid"}
     for clave, valor in persona.items():
         print(f"{clave}: {valor}")
     # Resultado:
     # nombre: Ana
     # edad: 25
     # ciudad: Madrid
     ```

---

### 3. **Listas y Tuplas en Python**
   - **Listas**:
     - **¿Qué es una lista?**: Piensa en una lista como una colección de cosas ordenadas. Como una lista de compras: puedes añadir cosas, quitar cosas, y reorganizar lo que hay en la lista.

     - **Ejemplo de lista y cómo añadir cosas**:
       ```python
       numeros = [10, 20, 30]  # Lista de números
       numeros.append(40)  # Añade el número 40 al final
       print(numeros)  # Resultado: [10, 20, 30, 40]
       ```
     
     - **Quitar algo de la lista**:
       ```python
       numeros.remove(20)  # Quita el número 20
       print(numeros)  # Resultado: [10, 30, 40]
       ```

     - **Ordenar y revertir la lista**:
       ```python
       numeros.sort()       # Ordena la lista
       print(numeros)       # Resultado: [10, 30, 40]
       numeros.reverse()    # Reversa el orden
       print(numeros)       # Resultado: [40, 30, 10]
       ```

   - **Tuplas**:
     - **¿Qué es una tupla?**: Es como una lista, pero una vez que la creas, ya no puedes cambiar nada. Si tienes datos que deben mantenerse sin cambios, las tuplas son ideales.

     - **Ejemplo de tupla**:
       ```python
       coordenadas = (10.5, 20.3)  # Una tupla con dos valores
       print(coordenadas[0])  # Resultado: 10.5
       ```

     - **Importante sobre las tuplas**: No puedes hacer algo como esto porque la tupla es "fija":
       ```python
       # Esto da error porque las tuplas no se pueden cambiar
       # coordenadas[0] = 15.0
       ```

¡Espero que esto lo haga más fácil y claro!
