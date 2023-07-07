## Función Constructora en JavaScript

La función constructora es una forma de crear objetos en JavaScript utilizando una función especial. Esta función se utiliza como una plantilla para crear nuevos objetos con propiedades y métodos comunes.

```javascript
// Definición de la función constructora
function Persona(nombre, edad, ocupacion) {
  this.nombre = nombre;
  this.edad = edad;
  this.ocupacion = ocupacion;

  this.saludar = function() {
    console.log("Hola, mi nombre es " + this.nombre + " y tengo " + this.edad + " años.");
  };
}

// Creación de objetos utilizando la función constructora
var persona1 = new Persona("Juan", 25, "Estudiante");
var persona2 = new Persona("María", 30, "Ingeniera");

// Acceso a propiedades y llamada a métodos de los objetos
console.log(persona1.nombre); // Juan
console.log(persona2.edad); // 30
persona1.saludar(); // Hola, mi nombre es Juan y tengo 25 años.
persona2.saludar(); // Hola, mi nombre es María y tengo 30 años.
