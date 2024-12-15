# Proyecto_Entornos_Desarrollo

# Resolución de Katas en Java

Este repositorio contiene las soluciones a dos problemas de programación en Java: **FizzBuzz** y **Tamagochi v1.0**. Además, se incluyen capturas del código y del proceso de depuración realizado en Eclipse.

---

## **Contenido del Repositorio**

### **Archivos de Código:**
1. `kata1`: Implementación del juego FizzBuzz, que imprime los números del 1 al 100 con las siguientes reglas:
   - "Fizz" si el número es divisible entre 3.
   - "Buzz" si es divisible entre 5.
   - "FizzBuzz" si es divisible entre ambos.
   - El número en caso contrario.

2. `kata2`: Simulación simplificada de un Tamagochi con los atributos hambre, energía y humor. Incluye métodos para jugar, comer y dormir, que alteran los atributos y muestran el estado del Tamagochi.

### **Capturas de Pantalla:**
Las capturas se encuentran en las carpetas `capturas` y se dividen en:
1. **Código Completo:** Imágenes de los archivos `kata1` y `kata2` abiertos en Eclipse.
2. **Proceso de Depuración:**
   - Breakpoints activos en líneas clave del código.
   - Estado de las variables en el panel de depuración.

---

## **Descripción de las Katas**

### **1. FizzBuzz**
El programa recorre los números del 1 al 100 y sigue las reglas del juego para imprimir:
- "Fizz" si un número es divisible entre 3.
- "Buzz" si es divisible entre 5.
- "FizzBuzz" si es divisible entre ambos.
- El número en caso contrario.

---

### **2. Tamagochi**
El programa simula un Tamagochi con los siguientes atributos iniciales:
- Hambre (`hunger`): 4
- Energía (`energy`): 4
- Humor (`mood`): 4

#### Métodos:
1. **`play()`**: Aumenta el hambre y el humor en 1, y disminuye la energía en 1.
2. **`eat()`**: Disminuye el hambre en 2 (mínimo 0) y la energía en 1.
3. **`sleep()`**: Aumenta la energía en 2.

#### Estados del Tamagochi:
- `:-)` (contento): Si el humor > 8.
- `(-_-)` (cansado): Si la energía < 3.
- `(-_-) zZZ` (dormido): Si la energía es 0 o después de dormir.
- `ఠ_ఠ` (enfadado): Si el humor < 2.
- `:-|` (normal): En cualquier otro caso.

---

## **Capturas del Proceso de Depuración**
En la carpetas `capturas` encontrarás:
1. **Breakpoints Activos:**
   - En las condiciones de "Fizz", "Buzz" y "FizzBuzz" en `kata1`.
   - En los métodos `play`, `eat`, y `sleep` de `kata2`.

2. **Estado de Variables:**
   - Panel de variables mostrando los cambios en `hunger`, `energy` y `mood` tras cada acción del Tamagochi.
   - Flujo de ejecución del bucle en `FizzBuzz`.



