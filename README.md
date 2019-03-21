# json-simpsons
var a = 1234;
var b = false;
//true es 1  y false es 0
var c = "palabra";
var d = ["perro", "gato", "ratón", 23, false];
var e = {ladra:"perro", maulla:"gato", musita:"ratón"};
var f = e.ladra;

var groening = {
simpsons:{padre:"Homero", madre:"Marge", hijos:["Bart","Lisa","Maggie"]},
flanders:{padre:"Ned", madre:"Maude (RIP)", hijos:["Rod","Todd"]},
vanhouten:{padre:"Kirk", madre:"Luann", hijos:["Milhouse"]},
muntz:{padre:false, madre:false, hijos:["nelson"]}
}

function setup() {
  createCanvas(400, 400);
	noLoop();
	print (groening.simpsons)
	//para que me aparezca la familia simpson pongo la variable seguida de un punto y la familia que quiero que aparezca
}

function draw() {
  background(220);
}


{
  "simpsons": {
    "padre": "Homero",
    "madre": "Marge",
    "hijos": [
      "Bart",
      "Lisa",
      "Maggie"
    ]
  },
  "flanders": {
    "padre": "Ned",
    "madre": "Maude (RIP)",
    "hijos": [
      "Rod",
      "Todd"
    ]
  },
  "vanhouten": {
    "padre": "Kirk",
    "madre": "Luann",
    "hijos": [
      "Milhouse"
    ]
  },
  "muntz": {
    "padre": false,
    "madre": false,
    "hijos": [
      "nelson"
    ]
  }
}
