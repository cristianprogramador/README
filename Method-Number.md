# Métodos de Number en JavaScript

Aquí tienes una lista de algunos de los métodos más comunes disponibles para los números en JavaScript:

- `toFixed(digits)`: Devuelve una cadena que representa el número con un número fijo de decimales, especificado por el parámetro `digits`.
- `toPrecision(precision)`: Devuelve una cadena que representa el número con una longitud total especificada por el parámetro `precision`.
- `toString([radix])`: Devuelve una cadena que representa el número en una base específica, donde el parámetro `radix` representa la base numérica (por defecto es 10).
- `toLocaleString()`: Devuelve una cadena que representa el número con formato específico según el idioma y las opciones del sistema.
- `valueOf()`: Devuelve el valor primitivo del objeto Number.
- `parseInt(string[, radix])`: Analiza una cadena y devuelve un entero, ignorando los caracteres no numéricos, donde el parámetro `radix` representa la base numérica (por defecto es 10).
- `parseFloat(string)`: Analiza una cadena y devuelve un número de punto flotante.
- `isFinite(number)`: Determina si un valor es un número finito. Devuelve un valor booleano.
- `isNaN(number)`: Determina si un valor no es un número (NaN). Devuelve un valor booleano.
- `isInteger(number)`: Determina si un valor es un número entero. Devuelve un valor booleano.
- `isSafeInteger(number)`: Determina si un valor es un número entero seguro (representable con precisión en JavaScript). Devuelve un valor booleano.
- `toExponential(fractionDigits)`: Devuelve una cadena que representa el número en notación exponencial, donde el parámetro `fractionDigits` representa la cantidad de dígitos después del punto decimal.
- `toPrecision(precision)`: Devuelve una cadena que representa el número con una longitud total especificada por el parámetro `precision`.

## Ejemplo de uso

Aquí tienes un ejemplo de cómo usar algunos de estos métodos:

```javascript
const number = 3.14159;

console.log(number.toFixed(2)); // Devuelve "3.14"
console.log(number.toString(2)); // Devuelve "11.0010010000111111011011"
console.log(parseInt("10")); // Devuelve 10
console.log(parseFloat("3.14")); // Devuelve 3.14
console.log(Number.isFinite(42)); // Devuelve true
console.log(Number.isNaN("hello")); // Devuelve true
console.log(Number.isInteger(10)); // Devuelve true
console.log(number.toExponential(2)); // Devuelve "3.14e+0"
