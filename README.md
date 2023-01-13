// Define tu fecha de nacimiento en formato 'YYYY-MM-DD'

let Fechacum = '2004-08-07';

let Fecha = new Date(birthdate);

let Fechaactaual = new Date();

let conversion1= currentDate - birthdateObject;

let Conversion2 = Math.floor(ageInMilliseconds / 31536000000);

console.log(`Tienes ${Conversion2} años`);


Clase para calcular el area de un rectangulo 

class Rectangulo {
  constructor(base, altura) {
    this.width = base; 
    this.height = altura; 
  }

  calculateArea() {
    return this.base * this.altura; 
  }
}

const myRectangle = new Rectangle(5, 10);
console.log(myRectangle.calculateArea()); // Output: 50



