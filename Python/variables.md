# Variables en Python

## En python una variable es un contenedor para almacenar datos. Puedes pensar en una variable como un nombre asociado a un valor. Aquí te muestro cómo crear y usar variables en Python:

- 1 Asignación de variables: Para asignar un valor a una variable, utilizamos el operador de asignación "=", seguido del valor que queremos asignar.

```python
nombre = "Juan"
edad = 25
altura = 1.75
```

- 2 Nombres de variables: Los nombres de variables pueden contener letras, números y guiones bajos, pero deben comenzar con una letra o un guion bajo. No pueden comenzar con un número y no pueden contener espacios en blanco. Además, Python distingue entre mayúsculas y minúsculas en los nombres de las variables.

```python
nombre = "Juan"  # Válido
edad = 25        # Válido
Altura = 1.75    # Válido, pero se recomienda usar minúsculas para variables
1edad = 25       # Inválido, no puede comenzar con un número
```

- 3 Tipos de datos: En Python, no necesitas declarar explícitamente el tipo de una variable. Python infiere automáticamente el tipo basado en el valor asignado.

```python
nombre = "Juan"  # Tipo: cadena de caracteres (string)
edad = 25        # Tipo: entero (int)
altura = 1.75    # Tipo: flotante (float)
```

- 4 Reasignación de variables: Puedes cambiar el valor de una variable simplemente asignándole un nuevo valor.

```python
edad = 26        # Cambiando el valor de la variable edad
```

- 5 Uso de variables en expresiones: Puedes usar variables en expresiones matemáticas y de cadena de caracteres.

```
suma = edad + 5
mensaje = "Hola, mi nombre es " + nombre
```

Recuerda que las variables te permiten almacenar y manipular datos de manera dinámica en Python. Espero que esta lección te ayude a entender mejor el concepto de variables en Python.