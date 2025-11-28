# Proyecto MuuLang

MuuLang es un lenguaje de programacion simplficado e intuitivo, enfocado en el area educativa tematizado con "vacas" y "granja" y diseñado para demostrar el funcionamiento interno de un compilador. 

## Información del Curso
* Materia: Programación en Sistemas de Base II
* Institución: Univerisidad Autonoma de Tamaulipas
* Semestre: Noveno semestre de 2025
* Profesor: Dante Adolfo Muñoz Quintero

## Integrantes del Equipo
-Angel Alejandro Cervantes de la Rosa - a2213332146
-Emmanuel Mendez de Jesus - a2213332184
-Fernando Aron Saenz Rico Perez - a2213332206
-Leonardo Yañez Reyna - a2183228019

## Estructura del Proyecto
Directorio Raíz
* main.py - Punto de entrada principal de la aplicación.
* analizador_lexico.py - Convierte el código fuente en una secuencia de tokens.
* parser.py - Verifica la estructura gramatical del código.
* nodo.py - Define la estructura de los nodos para la construcción del Árbol de Sintaxis Abstracta (AST).
* interfaz.py - Gestiona la interfaz gráfica (GUI) o de línea de comandos para interactuar con el compilador.
* interpreter.py - Módulo para la ejecución directa o interpretación del código fuente.
* programa.muu - Archivo de ejemplo con código fuente escrito en el lenguaje MuuLang para pruebas.
* tokens.txt - Archivo de salida o referencia que lista los tokens generados.

Módulo Semántico
* SemanticAnalyzer.py - Realiza el análisis semántico (comprobación de tipos, scopes, etc.).
* SymbolTable.py - Implementación de la Tabla de Símbolos para gestionar variables y funciones.

Módulo de Código Intermedio
* IRGenerator.py - Generador de Representación Intermedia (Intermediate Representation).
* IROptimizer.py - Módulo encargado de la optimización del código intermedio.
* FinalCodeGenerator.py - Generador de código final (target code) a partir de la representación intermedia optimizada.


## Requisitos y Dependencias

## Instrucciones de Compilación y Ejecución

## Ejemplos de Uso
