#### ESTRUCTURA NÚMERO 3  
# Funciones de Strings y Printing  

---

## 1. Descripción: Por qué y para qué se utiliza

Kotlin ofrece una rica variedad de funciones para manipular cadenas de texto (strings). Estas funciones te permiten realizar tareas como buscar, extraer, modificar y formatear strings. Son esenciales para trabajar con texto en cualquier aplicación, desde mostrar mensajes al usuario hasta procesar datos de archivos o APIs.

**Funciones de Impresión:**
Las funciones de impresión, como `println()`, te permiten mostrar texto y otros datos en la consola. Son cruciales para depurar tu código, mostrar resultados al usuario y registrar información durante la ejecución del programa.

### ¿Por qué son importantes?

* **Manipulación de texto**: Las funciones de strings te permiten trabajar con texto de manera eficiente y flexible.
* **Comunicación con el usuario**: Las funciones de impresión te permiten mostrar mensajes y resultados al usuario.
* **Depuración**: Imprimir valores y mensajes en la consola te ayuda a entender cómo se ejecuta tu programa y a encontrar errores.

### **Funciones de Strings**

| Función                     | Descripción                                    | Ejemplo                                  |
| :-------------------------- | :--------------------------------------------- | :--------------------------------------- |
| `.length`                  | Devuelve la longitud del string                | `"Hola".length → 4`                     |
| `.uppercase()`              | Convierte a mayúsculas                         | `"hola".uppercase() → "HOLA"`             |
| `.lowercase()`              | Convierte a minúsculas                         | `"HOLA".lowercase() → "hola"`             |
| `.replace("a", "o")`        | Reemplaza caracteres o palabras                | `"casa".replace("a", "o") → "coso"`       |
| `.contains("lo")`           | Verifica si contiene un texto específico       | `"Hola".contains("lo") → true`           |
| `.substring(1, 3)`          | Extrae una parte del texto                     | `"Hola".substring(1, 3) → "ol"`          |
| `.split(" ")`               | Divide el texto en partes                      | `"Hola mundo".split(" ") → ["Hola", "mundo"]` |
| `.trim()`                   | Elimina espacios en blanco al inicio y al final | `" Hola ".trim() → "Hola"`               |

### **Funciones de Printing (Impresión en Pantalla)**

| Función                 | Descripción                   | Ejemplo                    |
| :---------------------- | :---------------------------- | :------------------------- |
| `print("Hola")`          | Imprime sin salto de línea     | `print("Hola") → Hola`     |
| `println("Hola")`        | Imprime con salto de línea     | `println("Hola") → Hola⏎` |
| `printf("Hola %s", "Mundo")` | Imprime con formato           | `printf("Hola %s", "Mundo") → Hola Mundo` |

--- 

## 2. Genere un ejemplo internamente en el recuadro.  
- Utilice un editor de código para lograrlo.  

🔗 **[LINK DE CÓDIGO](https://pl.kotl.in/NMnOrcWbm?theme=darcula&readOnly=true)**  


🔗 **[LINK DEL AUDIO]()**  
🔗 **[LINK CÓDIGO PROBADO POR US Y GUARDADO EN GITHUB]()**.

**ALGORITMO CREADO Y EXPLICACION DE COMO FUNCIONA LA ESTRUCTURA**
```kotlin
// EJERCICIO CREADO EN KOTLIN
fun main() {
    // En nuestros codigos creados nosotros vamos a estar trabajando con strings.
    val nombreCompleto = "Santiago Lopera"
    val saludo = "Hola, $nombreCompleto" // Interpolación de strings.

    // Aqui vamos a mostrar el saludo
    println(saludo)

    // Luego vamos a mostrar la Longitud del nombre
    val longitudNombre = nombreCompleto.length
    println("La longitud del nombre es: $longitudNombre")

    // Luego vamos a mostrar el apellido en mayúsculas
    val indiceEspacio = nombreCompleto.indexOf(" ")
    if (indiceEspacio != -1) {
        val apellidoMayusculas = nombreCompleto.substring(indiceEspacio + 1).uppercase()
        println("Apellido en mayúsculas: $apellidoMayusculas")
    } else {
        println("No se encontró un espacio en el nombre completo.")
    }

    // Verificamos si el nombre contiene "ago"
    val contieneAgo = nombreCompleto.contains("ago")
    println("¿El nombre contiene 'ago'?: $contieneAgo")

    // Dividimos el nombre en nombre y apellido
    val partesNombre = nombreCompleto.split(" ")
    if (partesNombre.size >= 2) {
        println("Nombre: ${partesNombre[0]}, Apellido: ${partesNombre[1]}")
    } else {
        println("No se pudo dividir el nombre en nombre y apellido.")
    }
}
```

