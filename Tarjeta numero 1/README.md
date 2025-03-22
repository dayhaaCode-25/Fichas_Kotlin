# ESTRUCTURA NÚMERO 1: MANEJO DE VARIABLES EN KOTLIN

## Introducción

En Kotlin, las variables son elementos fundamentales para almacenar y manipular datos. Cada variable tiene un tipo de dato específico que define el tipo de valor que puede contener. En este artículo, exploraremos los tipos de datos básicos en Kotlin y cómo declarar variables.

## Tipos de Datos Básicos

* **Int:** Números enteros (ej: 10, -5, 0).
* **Double:** Números de punto flotante de doble precisión (ej: 3.14, -2.5).
* **Float:** Números de punto flotante de precisión simple (ej: 3.14f, -2.5f). (Nota: se agrega "f" al final del numero).
* **Boolean:** Valores lógicos (true o false).
* **Char:** Caracteres individuales (ej: 'a', 'Z', '5').
* **String:** Cadenas de texto (ej: "Hola", "Kotlin").

## Declaración de Variables

En Kotlin, se utilizan las palabras clave `val` y `var` para declarar variables:

* **val:** Se utiliza para variables inmutables (de solo lectura). Su valor no puede cambiar después de la asignación inicial.
* **var:** Se utiliza para variables mutables (de lectura y escritura). Su valor puede cambiar a lo largo del programa.

## Ejemplo de Código

A continuación, se muestra un ejemplo de cómo declarar y utilizar variables en Kotlin:

```kotlin
fun main() {
    val nombre: String = "Juan Pérez"
    var edad: Int = 30
    val altura: Double = 1.75
    val esEstudiante: Boolean = true
    val inicial: Char = 'J'

    println("Nombre: $nombre")
    println("Edad: $edad")
    println("Altura: $altura")
    println("¿Es estudiante?: $esEstudiante")
    println("Inicial: $inicial")

    edad = 31 // Cambiando el valor de la variable mutable "edad"
    println("Nueva edad: $edad")
}
