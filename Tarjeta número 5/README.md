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

