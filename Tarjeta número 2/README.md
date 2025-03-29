#### ESTRUCTURA NÚMERO 2  
# Operadores Math Lógicos  

---

## 1. Descripción: Por qué y para qué se utilizan

Los operadores matemáticos y lógicos son herramientas fundamentales en Kotlin (y en la programación en general) que te permiten realizar cálculos y tomar decisiones dentro de tu código.

**Operadores matemáticos**: Se utilizan para realizar operaciones aritméticas básicas como suma, resta, multiplicación y división. También incluyen operadores para obtener el resto de una división (módulo) y para trabajar con potencias.
**Operadores lógicos**: Se utilizan para combinar o negar condiciones booleanas (verdadero o falso). Esto te permite crear expresiones lógicas más complejas para controlar el flujo de tu programa.

### ¿Qué son y para qué sirven?

Los operadores matemáticos y lógicos son herramientas fundamentales en Kotlin (y en la programación en general) que te permiten realizar cálculos y tomar decisiones dentro de tu código.

**Operadores matemáticos**: Se utilizan para realizar operaciones aritméticas básicas como suma, resta, multiplicación y división. También incluyen operadores para obtener el resto de una división (módulo) y para trabajar con potencias.
**Operadores lógicos**: Se utilizan para combinar o negar condiciones booleanas (verdadero o falso). Esto te permite crear expresiones lógicas más complejas para controlar el flujo de tu programa.

### ¿Por qué son importantes?

**Cálculos**: Los operadores matemáticos son esenciales para realizar cualquier tipo de cálculo numérico en tus programas.
**Toma de decisiones**: Los operadores lógicos te permiten crear condiciones que determinan qué partes de tu código se ejecutan y cuáles no. Esto es crucial para la lógica de cualquier programa.
**Control de flujo**: Al combinar operadores lógicos con estructuras de control como `if` y `when`, puedes crear programas que se adaptan a diferentes situaciones y entradas de datos.

### **Operadores Matemáticos**

| Operador | Descripción                  | Ejemplo       |
| :------- | :--------------------------- | :------------ |
| `+`      | Suma                         | `5 + 3 = 8`   |
| `-`      | Resta                        | `10 - 4 = 6`  |
| `*`      | Multiplicación               | `6 * 2 = 12`  |
| `/`      | División                     | `8 / 2 = 4`   |
| `%`      | Módulo (resto de la división) | `10 % 3 = 1`  |
| `**`     | Potencia                     | `2 ** 3 = 8`  |
| `//`     | División entera              | `10 // 3 = 3` |

### **Operadores Lógicos**

| Operador | Descripción                                    | Ejemplo                                   |
| :------- | :--------------------------------------------- | :---------------------------------------- |
| `&&`     | AND (verdadero si ambas condiciones son ciertas) | `(5 > 3) && (2 < 4) → true`               |
| `||`     | OR (verdadero si al menos una condición es cierta) | `(5 > 3) || (2 > 4) → true`               |
| `!`      | NOT (invierte el valor de una condición)        | `!(5 > 3) → false`                        |

---

## 2. Genere un ejemplo internamente en el recuadro.  
- Utilice un editor de código para lograrlo.  

🔗 **[LINK DE CÓDIGO](https://pl.kotl.in/EMhr6h7oE?theme=darcula&readOnly=true)**  

### CREAR ALGORITMO PROPIO Y EXPLIQUELO PASO A PASO 
- Genere el link del audio y el link de GitHub.  

🔗 **[LINK DEL AUDIO]()**  
🔗 **[LINK CÓDIGO PROBADO POR US Y GUARDADO EN GITHUB]()**.

**ALGORITMO CREADO Y EXPLICACION DE COMO FUNCIONA LA ESTRUCTURA**
```kotlin
// EJERCICIO CREADO EN KOTLIN
fun main() {
    // Nosotros vamos a realizar en nuestro segundo codigo algunos cálculos y comparaciones.
    val num1 = 15
    val num2 = 7

    // Operaciones matemáticas:
    val suma = num1 + num2 // Sumamos num1 y num2.
    val resta = num1 - num2 // Restamos num2 de num1.
    val multiplicacion = num1 * num2 // Multiplicamos num1 por num2.
    val division = num1 / num2 // Dividimos num1 entre num2.
    val modulo = num1 % num2 // Obtenemos el resto de la división.

    println("Suma: $suma")
    println("Resta: $resta")
    println("Multiplicación: $multiplicacion")
    println("División: $division")
    println("Módulo: $modulo")

    // Comparaciones lógicas:
    val esMayor = num1 > num2 // ¿Es num1 mayor que num2?
    val esIgual = num1 == 15 // ¿Es num1 igual a 15?

    println("¿Num1 es mayor que Num2?: $esMayor")
    println("¿Num1 es igual a 15?: $esIgual")

    // Operadores lógicos combinados:
    val resultadoAND = esMayor && esIgual // ¿Ambas condiciones son verdaderas?
    val resultadoOR = esMayor || !esIgual // ¿Alguna condición es verdadera?

    println("Resultado AND: $resultadoAND")
    println("Resultado OR: $resultadoOR")
}
```

