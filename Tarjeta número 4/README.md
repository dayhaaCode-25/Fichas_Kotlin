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

🔗 **[LINK DE CÓDIGO](https://pl.kotl.in/dLtTjMH1P?readOnly=true&theme=darcula)**  

