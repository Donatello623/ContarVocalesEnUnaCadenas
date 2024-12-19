# Proyecto de Contador de Vocales en C++

Este proyecto en C++ tiene como objetivo contar el número de vocales en una cadena de caracteres introducida por el usuario. El programa define una función que verifica si un carácter es una vocal y luego recorre la cadena, contando cuántas vocales contiene.

## Descripción

El programa solicita al usuario ingresar una cadena de texto y luego recorre cada carácter de esa cadena. Para cada carácter, verifica si es una vocal (sin importar si es mayúscula o minúscula). Utilizando una función llamada `esVocal`, el programa cuenta el total de vocales y lo muestra al usuario.

### Pasos del programa:
1. Solicita al usuario ingresar una cadena de caracteres.
2. Recorre cada carácter de la cadena y verifica si es una vocal.
3. Cuenta cuántas vocales hay en la cadena.
4. Muestra el total de vocales en la salida.

## Cómo Ejecutarlo

### Requisitos
- Un compilador de C++ (por ejemplo, g++, Clang, etc.).
- Un entorno de desarrollo adecuado para compilar y ejecutar código en C++.

### Instrucciones

1. **Clonar el repositorio** (si el proyecto está en un repositorio Git):
   ```bash
   git clone <URL-del-repositorio>
   cd <nombre-del-directorio>
Compilar el código: Si estás usando g++, ejecuta el siguiente comando en la terminal:

bash
Copiar código
g++ -o contador_vocales contador_vocales.cpp
Ejecutar el programa: Una vez compilado, ejecuta el programa con:

bash
Copiar código
./contador_vocales
El programa pedirá que ingreses una cadena y luego mostrará el número total de vocales en la cadena.