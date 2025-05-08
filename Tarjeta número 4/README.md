#### ESTRUCTURA NÚMERO 4  
# Control de Flujo  

---  

## 1. Describa el por qué y para qué se utiliza.  
El **Control de Flujo** en programación permite **dirigir la ejecución de un programa** basándose en **condiciones, repeticiones y excepciones**. Se utiliza para tomar decisiones, repetir acciones y manejar errores de manera estructurada, mejorando la lógica y eficiencia del código.  

### **Condicionales (Toma de Decisiones)**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `if` | Ejecuta un bloque si la condición es verdadera | `if (x > 0) { println("Es positivo") }` |
| `if-else` | Ejecuta un bloque si es verdadero, otro si es falso | `if (x > 0) { println("Positivo") } else { println("Negativo") }` |
| `when` | Alternativa a múltiples `if-else` | `when(x) { 1 -> println("Uno") 2 -> println("Dos") else -> println("Otro") }` |

---

### **Bucles (Repetición de Código)**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `for` | Itera sobre un rango o colección | `for (i in 1..5) { println(i) }` |
| `while` | Repite mientras la condición sea verdadera | `while (x < 10) { println(x); x++ }` |
| `do-while` | Ejecuta al menos una vez y luego evalúa la condición | `do { println(x); x++ } while (x < 10)` |

---

### **Manejo de Excepciones (Errores)**  

| Estructura | Descripción | Ejemplo |
|------------|------------|---------|
| `try-catch` | Captura errores y permite manejarlos | `try { val res = 10 / 0 } catch (e: Exception) { println("Error") }` |
| `finally` | Se ejecuta siempre, con o sin error | `try { ... } catch (e: Exception) { ... } finally { println("Fin") }` |

---

## 2. Genere un ejemplo internamente en el recuadro.  
- Utilice un editor de código para lograrlo.
- **[LINK DE CÓDIGO](https://pl.kotl.in/dLtTjMH1P?readOnly=true&theme=darcula)**

```kotlin
// EJEMPLO #1 EN CÓDIGO KOTLIN - IF
fun main() {
    val edad = 20
    if(edad>=18){
        println("Eres mayor de edad")
    }
}
```
```Kotlin
// EJEMPLO #2 EN CÓDIGO KOTLIN - ELSE
fun main(){
   val edad = 16
   if (edad >= 18){
       println("Eres mayor de edad")
   } else {
       println("Eres menor de edad")
   }
}
```
```Kotlin
// EJEMPLO #3 EN CÓDIGO KOTLIN - ELSE IF
fun main(){
   val puntuacion = 90
   if (puntuacion >= 90) {
       println("Excelente")
   } else if (puntuacion >= 80){
       println("Muy bien")
   } else if (puntuacion >= 70) {
       println("Bien")
       } else {
           println("A mejorar")
   }
}
```
```Kotlin
// EJEMPLO #4 EN CÓDIGO KOTLIN - WHEN
fun main() {
    val numero = 3

    when (numero) {
        1 -> println("El número es uno.")
        2 -> println("El número es dos.")
        3 -> println("El número es tres.")
        in 4..10 -> println("El número está entre 4 y 10.")
        else -> println("El número no está en la lista.")
    }
}
```






