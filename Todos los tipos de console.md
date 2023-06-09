# console.log(): Muestra un mensaje en la consola. Puede contener variables, expresiones y objetos para mostrar su valor.

const name = "John";
const age = 30;
console.log("¡Hola, mi nombre es", nombre, "y tengo", edad, "años de edad!");


# console.error(): Muestra un mensaje de error en la consola. Se utiliza para indicar errores o problemas en el código.

const x = 10;
if (x < 5) {
console.error("Error: x es mayor que 5");
}

# console.warn(): Muestra un mensaje de advertencia en la consola. Se utiliza para indicar advertencias o situaciones potencialmente problemáticas en el código.

const temperature = 90;
if (temperature > 100) {
console.warn("Warning:La temperatura es muy alta.!");
}

# console.info(): Muestra un mensaje informativo en la consola. Se utiliza para proporcionar información adicional sobre el código.

const user = {
name: "Alice",
age: 25,
city: "London"
};
console.info("User:", user);

# console.debug(): Muestra un mensaje de depuración en la consola. Se utiliza para imprimir mensajes de depuración durante el desarrollo.

function calculateSum(a, b) {
console.debug("Calculating sum...");
const sum = a + b;
console.debug("Sum calculated:", sum);
return sum;
}
calculateSum(5, 3);

# console.assert(): Comprueba si una afirmación es verdadera. Si la afirmación es falsa, muestra un mensaje de error en la consola.

function divide(a, b) {
console.assert(b !== 0, "Error: No se permite la división por cero.");
return a / b;
}
divide(10, 0);

# console.clear(): Limpia la consola y borra todos los mensajes anteriores.

console.clear();
console.log("Este mensaje será el único que se mostrará en la consola");

# console.count(): Registra el número de veces que se ha llamado a

function processItem(item) {
console.count("Processed items");
// Resto del código de procesamiento del elemento
}
processItem("A");
processItem("B");
processItem("C");

# console.table(): Muestra datos tabulares en forma de tabla en la consola. Acepta un array de objetos o una matriz y muestra sus propiedades como columnas.

const users = [
{ name: "John", age: 30 },
{ name: "Alice", age: 25 },
{ name: "Bob", age: 35 }
];
console.table(users);

# console.group(), console.groupCollapsed(), console.groupEnd(): Agrupa mensajes en la consola. Se utilizan para crear grupos de mensajes relacionados y ayudar a organizar la salida en la consola.

console.group("Outer Group");
console.log("Message inside outer group");
console.groupCollapsed("Inner Group");
console.log("Message inside inner group");
console.groupEnd();
console.log("Message outside groups");
console.groupEnd();
