# Métodos de Set en JavaScript

Aquí tienes una lista de los métodos más comunes disponibles para el objeto Set en JavaScript:

- `add(value)`: Agrega un elemento al final del conjunto.
- `delete(value)`: Elimina un elemento del conjunto si existe.
- `has(value)`: Verifica si un elemento está presente en el conjunto. Devuelve un valor booleano.
- `clear()`: Elimina todos los elementos del conjunto, dejándolo vacío.
- `size`: Propiedad de solo lectura que devuelve la cantidad de elementos en el conjunto.
- `values()`: Devuelve un iterador con todos los valores del conjunto.
- `forEach(callbackFn[, thisArg])`: Ejecuta una función de devolución de llamada para cada elemento del conjunto.
- `entries()`: Devuelve un iterador con pares [valor, valor] para cada elemento del conjunto.
- `keys()`: Es similar a `values()`, devuelve un iterador con los valores del conjunto.
- `Symbol.iterator`: Método que permite al conjunto ser iterable, por ejemplo, mediante el uso de `for...of` loops.

## Ejemplo de uso

Aquí tienes un ejemplo de cómo usar algunos de estos métodos:

```javascript
const mySet = new Set();

mySet.add(1);
mySet.add(2);
mySet.add(3);

console.log(mySet.has(2)); // Devuelve true

mySet.delete(2);

console.log(mySet.size); // Devuelve 2

mySet.forEach((value) => {
  console.log(value);
});
