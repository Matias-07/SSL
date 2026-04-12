# TP0 - Hello, World! en C

## Descripcion

Primer trabajo practico de la materia Sintaxis y Semantica de los Lenguajes.
Consiste en configurar el entorno de desarrollo, escribir, compilar y ejecutar un programa "Hello, World!" en C23.

## Compilador seleccionado

**Apple Clang** (incluido en Xcode Command Line Tools)

## Version del compilador

Apple clang version 21.0.0 (clang-2100.0.123.102)

### Version del lenguaje C compilada

C23 (__STDC_VERSION__ = 202311)

# Compilar
clang -std=c2x hello.c -o hello

# Ejecutar
./hello

# Ejecutar con salida redireccionada
./hello > output.txt

