#### ESTRUCTURA NÚMERO 5  
# Estructuras de Decisión, Control y Manejo de Errores  

---  

## 1. Describa el por qué y para qué se utiliza.  
Las **estructuras de decisión y control** permiten tomar **decisiones dentro de un programa** y definir la **lógica del flujo de ejecución**, mientras que el **manejo de errores** ayuda a prevenir que los programas fallen inesperadamente.  

### **Estructuras de Decisión**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `if` | Ejecuta un bloque si la condición es verdadera | `if (x > 0) { println("Es positivo") }` |
| `if-else` | Ejecuta un bloque si es verdadero, otro si es falso | `if (x > 0) { println("Positivo") } else { println("Negativo") }` |
| `when` | Alternativa a múltiples `if-else` | `when(x) { 1 -> println("Uno") 2 -> println("Dos") else -> println("Otro") }` |

---

### **Estructuras de Control**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `for` | Itera sobre un rango o colección | `for (i in 1..5) { println(i) }` |
| `while` | Repite mientras la condición sea verdadera | `while (x < 10) { println(x); x++ }` |
| `do-while` | Ejecuta al menos una vez antes de evaluar la condición | `do { println(x); x++ } while (x < 10)` |

---

### **Manejo de Errores**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `try-catch` | Captura y maneja errores en tiempo de ejecución | `try { val res = 10 / 0 } catch (e: Exception) { println("Error") }` |
| `finally` | Se ejecuta siempre, con o sin error | `try { ... } catch (e: Exception) { ... } finally { println("Fin") }` |
| `throw` | Lanza una excepción personalizada | `throw IllegalArgumentException("Valor inválido")` |

---

## 2. Genere un ejemplo internamente en el recuadro.  
- Utilice un editor de código para lograrlo.  

🔗 **[LINK DE CÓDIGO](https://pl.kotl.in/8X8c83CB0?theme=darcula&readOnly=true)**  

**Ejemplo - Condicionales (if-else):**
```kotlin
// EJEMPLO EN CÓDIGO KOTLIN
fun verificarEdad(edad: Int) {
    if (edad >= 18) {
        println("Puede votar")
    } else {
        println("No puede votar")
    }
}
fun main() {
    verificarEdad(20) // Imprime "Puede votar"
    verificarEdad(15) // Imprime "No puede votar"
}
```
**Ejemplo - Bucles (for, while):**
```kotlin
// EJEMPLO EN CÓDIGO KOTLIN
fun imprimirNumeros() {
    // Bucle for
    for (i in 1..10) {
        println(i)
    }

    // Bucle while con entrada simulada.
    val respuestas = listOf("no", "no", "si") // Simulamos la entrada del usuario.
    var i = 0;
    var respuesta = "";
    while (respuesta != "si") {
        println("¿Desea continuar? (si/no)")
        respuesta = respuestas[i];
        println(respuesta);
        i++;
    }
}

fun main() {
    imprimirNumeros()
}
```
**Ejemplo - Sentencias when:**
```kotlin
// EJEMPLO EN CÓDIGO KOTLIN
fun diaDeLaSemana(dia: Int) {
    when (dia) {
        1 -> println("Lunes")
        2 -> println("Martes")
        3 -> println("Miércoles")
        4 -> println("Jueves")
        5 -> println("Viernes")
        6 -> println("Sábado")
        7 -> println("Domingo")
        else -> println("Día inválido")
    }
}

fun main() {
    diaDeLaSemana(3) // Imprime "Miércoles"
    diaDeLaSemana(8) // Imprime "Día inválido"
}
```
**Ejemplo - Códigos de error:**
```kotlin
// EJEMPLO EN CÓDIGO KOTLIN
fun encontrarElemento(lista: List<Int>, elemento: Int): Int {
    for (i in lista.indices) {
        if (lista[i] == elemento) {
            return i // Devuelve el índice si se encuentra el elemento
        }
    }
    return -1 // Devuelve -1 si el elemento no se encuentra
}

fun main() {
    val lista = listOf(1, 2, 3, 4, 5)
    val indice = encontrarElemento(lista, 3)
    if (indice != -1) {
        println("Elemento encontrado en el índice $indice")
    } else {
        println("Elemento no encontrado")
    }
}
```


