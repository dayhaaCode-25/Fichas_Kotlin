#### ESTRUCTURA NÚMERO 1  
# MANEJO DE VARIABLES  

---

1. **Describa el por qué y para qué se utiliza.**

Sabemos que en Kotlin, las variables son esenciales para almacenar y manipular datos. Las podemos imaginar como contenedores que guardan una información. Cada variable tiene un nombre único y un tipo de dato que define qué tipo de información puede almacenar.

## Tipos de Datos Comunes:

* **Int:** Números enteros (ejemplo: 1, 10, -5).
* **Double:** Números decimales con alta precisión (ejemplo: 3.1416, 2.5).
* **Float:** Números decimales con menor precisión que Double.
* **Boolean:** Valores lógicos (verdadero o falso, `true` o `false`).
* **Char:** Un solo carácter (ejemplo: 'a', '?', '5').
* **String:** Cadenas de texto (ejemplo: "Hola", "Soy", "Dayhana").

## Declaración de Variables:

* **val:** Se usa para declarar variables inmutables, es decir, su valor no puede cambiar después de la asignación inicial.
* **var:** Se usa para declarar variables mutables, el cual el valor puede modificarse a lo largo del programa.
   
2. **Genere un ejemplo internamente en el recuadro.**  

   - Utilice un editor de código para lograrlo.  

🔗 **[LINK DE CODIGO DEL EJEMPLO](https://pl.kotl.in/GIx__N5YU?theme=darcula&readOnly=true)** 

### CREAR ALGORITMO PROPIO Y EXPLIQUELO PASO A PASO 
- Genere el link del audio y el link de GitHub.  

🔗 **[LINK DEL AUDIO]()**  
🔗 **[LINK CÓDIGO PROBADO POR US Y GUARDADO EN GITHUB](https://github.com/dayhaaCode-25/Fichas_Kotlin/blob/39c4e4b7160b0ca620b97ee262ca7a49f6fb212a/Tarjeta%20numero%201/MANEJO%20DE%20VARIABLES.PNG)**.

**ALGORITMO CREADO Y EXPLICACION DE COMO FUNCIONA LA ESTRUCTURA**
```kotlin
// EJERCICIO CREADO EN KOTLIN
fun main() {
    // Nuestro codigo creado sera sobre la declaración de variables relacionadas con un estudiante.
    val nombreEstudiante: String = "Santiago Lopera" // 'val' porque el nombre no cambiará
    var calificacion: Double = 8.5 // 'var' porque la calificación puede actualizarse
    val esEstudianteMatriculado: Boolean = true // 'val' porque el estado de matriculación no cambia

    // Imprimir información inicial
    println("Nombre del estudiante: $nombreEstudiante")
    println("Calificación inicial: $calificacion")
    println("¿Estudiante matriculado?: $esEstudianteMatriculado")

    // Simular una actualización de calificación
    calificacion = 9.2 // Modificamos la calificación

    // Imprimir la calificación actualizada
    println("Calificación actualizada: $calificacion")

    // ejemplo de variable entera y de caracter
    val edadEstudiante: Int = 18
    val grupoEstudiante: Char = 'A'

    //Impresión de variables enteras y de caracter.
    println("Edad del estudiante: $edadEstudiante")
    println("Grupo del estudiante: $grupoEstudiante")
}
```
