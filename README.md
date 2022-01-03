# Kelvin-Converter
Codecademy Project in JavaScript

// Kelvin temp for the day
const kelvin =290;
// converts kelvin to celsius
const celsius = kelvin - 273;
// converts celsius to fahrenheit
let fahrenheit = ((celsius * (9/5)) + 32);
// rounds down fahrenheit temp after conversion
fahrenheit = Math.floor(fahrenheit);
// displays temp in  fahrenheit
console.log('The temperature is ' + fahrenheit + ' degrees Fahrenheit.');

// converts celsius to newton scale
newton = celsius * (33/100);
// rounds down newton temp after conversion
newton = Math.floor(newton);
// displays newton temp
console.log('The temperature is ' + newton + ' degrees Newton.');
