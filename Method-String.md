# Métodos de String en JavaScript

Aquí tienes una lista de algunos de los métodos más comunes disponibles para las cadenas de texto en JavaScript:

- `length`: Propiedad de solo lectura que devuelve la longitud de la cadena.
- `charAt(index)`: Devuelve el carácter en la posición especificada por el índice.
- `charCodeAt(index)`: Devuelve el valor Unicode del carácter en la posición especificada por el índice.
- `concat(string1[, string2[, ...[, stringN]]])`: Combina dos o más cadenas y devuelve una nueva cadena resultante.
- `indexOf(searchValue[, startIndex])`: Devuelve el índice de la primera aparición de un valor de búsqueda en la cadena, o -1 si no se encuentra.
- `lastIndexOf(searchValue[, startIndex])`: Devuelve el índice de la última aparición de un valor de búsqueda en la cadena, o -1 si no se encuentra.
- `startsWith(searchString[, startIndex])`: Verifica si la cadena comienza con el valor de búsqueda especificado. Devuelve un valor booleano.
- `endsWith(searchString[, length])`: Verifica si la cadena termina con el valor de búsqueda especificado. Devuelve un valor booleano.
- `includes(searchString[, startIndex])`: Verifica si la cadena contiene el valor de búsqueda especificado. Devuelve un valor booleano.
- `substring(startIndex[, endIndex])`: Devuelve una subcadena de la cadena, especificada por los índices de inicio y fin.
- `slice(startIndex[, endIndex])`: Devuelve una copia superficial (shallow copy) de una porción de la cadena, especificada por los índices de inicio y fin.
- `toUpperCase()`: Devuelve una nueva cadena con todos los caracteres en mayúsculas.
- `toLowerCase()`: Devuelve una nueva cadena con todos los caracteres en minúsculas.
- `trim()`: Devuelve una nueva cadena eliminando los espacios en blanco al inicio y al final de la cadena.
- `replace(searchValue, replaceValue)`: Reemplaza la primera aparición de un valor de búsqueda por un valor de reemplazo en la cadena.
- `replaceAll(searchValue, replaceValue)`: Reemplaza todas las apariciones de un valor de búsqueda por un valor de reemplazo en la cadena.
- `split(separator[, limit])`: Divide la cadena en un arreglo de subcadenas utilizando un separador especificado.
- `match(regexp)`: Devuelve un arreglo de todas las coincidencias de una expresión regular en la cadena.
- `search(regexp)`: Busca una coincidencia entre una expresión regular y la cadena, y devuelve el índice de la primera coincidencia o -1 si no se encuentra.
- `toLocaleLowerCase()`: Devuelve una nueva cadena con todos los caracteres en minúsculas, de acuerdo con las convenciones de idioma específicas.
- `toLocaleUpperCase()`: Devuelve una nueva cadena con todos los caracteres en mayúsculas, de acuerdo con las convenciones de idioma específicas.

## Ejemplo de uso

Aquí tienes un ejemplo de cómo usar algunos de estos métodos:

```javascript
const str = "Hola, mundo!";

console.log(str.length); // Devuelve 12
console.log(str.charAt(0)); // Devuelve "H"
console.log(str.indexOf("mundo")); // Devuelve
