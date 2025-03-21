
# **Ejercicio 1: Calculadora de Comparaciones y Repetición**

---

- **¿Sabías que `Scanner.nextInt()` no consume el salto de línea?** Si mezclas tipos de entrada (por ejemplo, int y luego String), puede traerte problemas.
- **El operador `%` no es solo para saber si un número es par… 👀**
- Usa `Math.round()` para redondear si quieres impresionar, pero recuerda que el casting explícito también tiene su encanto.
- El `while(true)` tiene su fuerza, pero salir de él con un `break` bien ubicado es arte ninja.
- **No subestimes `Scanner.nextLine()` para hacer una pregunta tipo “¿Deseas continuar?” y evaluar con `.equalsIgnoreCase("si")`.**

documentacion:
**Primero importamos la clase Scanner para permitir la entrada de datos desde la consola. 
**Luego, creamos un objeto Scanner input que nos servirá para capturar lo que el usuario ingrese. 
**Declaramos dos variables numero1 y numero2 (int). Usamos input.nextInt(); para almacenar los datos  ingresados por el usuario.
**A continuación, verificamos cuál de los dos números es mayor usando if-else. Si numero1 es mayor que numero2, mostramos un mensaje indicando que numero1 es el mayor; en caso contrario, mostramos que numero2 es el mayor.
** y asi sucesivamente con el menor y el igual.
** y para preguntar al usuario si quiere seguir usando la calculadorra de comparaciones usamos un Scanner.nextLine( " quiere seguir usando la calculadora " );
** y con el equalsIgnoreCase("si") en caso de que sea lo contrario el programa terminara su proceso.