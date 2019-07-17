# 100 Days Of Code - Log

### Day 0: Julio 10, 2019 
##### Descubriendo JavaScript

**Today's Progress**: Funciones JS

**Thoughts:** Dia de descubrimiento de las funciones de JavaScript, algo esencial para trabajar el dia a dia, vamos a definir que es una funcion, las funciones son uno de los pilares fundamentales en JavaScript. Una función es un procedimiento en JavaScript—un conjunto de sentencias que realizan una tarea o calculan un valor. Para usar una función, debe definirla en algún lugar del ámbito desde el cual desea llamarla.
Hemos empezado aplicando la teoria, para luego empezar con 13 ejercicios que son los siguientes:
(todavia esta costando entender y trabajar con el concepto de las funciones pero durante esta semana seguiremos practicando hasta tenerlo 100%100 interiorizado)


<!-- function num(entero) {

    for (let i = 0; i <= 20; i++) {

        if (i == 1) {

        }
        if (i == 3) {

        }
    }
    return entero;
}

alert(num(10)) 




//-------------------------------------------------------Ejercicio 6-7-8--------------------------------------------------------------------

// function celsiusToFahrenheit(celsius) {

//     let gradosF = (celsius * 9 / 5) + 32;

//     return gradosF;
// }

// function fahrenheitToCelsius(fahrenheit) {

//     let gradosC = (fahrenheit - 32 * 5) / 9;

//     return gradosC;
// }

// function convertTemperature(str, grados) {

//     let temp = 0;
    
//     if (str == "Celsius") {
//         temp = celsiusToFahrenheit(grados);
//     }

//     if (str == "Fahrenheit") {
//         temp = fahrenheitToCelsius(grados);
//     }

//     return temp;
// }

// alert(convertTemperature("Fahrenheit", 50));
// alert(convertTemperature("Celsius", 20));

//---------------------------------------------------------Ejercicio 5 ----------------------------------------------------------------


// function calculadogAge(edadPerro,multi) {
//     edadPerro *= multi;
//     let edad = "¡Tu perrito tiene" + edadPerro +  "años en años de perros!"
//     return edadPerro;

// }

// console.log(calculadogAge(5, 8 ))
// console.log(calculadogAge(10, 4))
// console.log(calculadogAge(20,2))



//---------------------------------------------------------Ejercicio 4 ----------------------------------------------------------------

// function tellFortune(hijos, nombre, ubicacion, titulo) {
// let texto = "Seras " + titulo + " en " + ubicacion + " ,y estaras casada con" + nombre + "y tendras" + hijos + " hijos"

// return texto;

// }

// console.log(tellFortune(" 9 "," Maria "," Ledteach "," CTO "))


//---------------------------------------------------------Ejercicio 3 ---------------------------------------------------------------------


// function calculo(arr) {

//     let flag = false;

//     if (arr[0] == arr[1] || arr[1] == arr[2]) {

//         flag= true;

//     }
//     if (arr[1] == 4) {

//         flag = false;
//     }

//     return flag;

// }

// console.log(calculo([1, 2, 3]))
// console.log(calculo([1, 1, 3]))
// console.log(calculo([1, 4, 3]))


//------------------------------------------------------------Ejercicio 2 ---------------------------------------------------------------



// function miFuncion(arr,str) {

//     for (let i = 0; i < arr.length; i++) {
//         if (arr[i] == str) {

//             return i;
//         }

//     }
// }

// let arr1 = ["hola", "mundo"]
// let str1 = "mundo"
// let posicion = miFuncion(arr1, str1);
// console.log(posicion)





//-----------------------------------------------------------Ejercicio 1 ------------------------------------------------------------------


// function division(numero) {   
//     numero /= 100;
//     return numero;
// }
// console.log(division(40))


//---------------------------------------------------------------function3--------------------------------------------------------------------


// let animal = prompt("Elige un animal")
// let mamiferos = ['Canguro', 'Monos', 'Antílope', 'Vaca', 'Caballo', 'Cerdo', 'Oveja', 'Cabra', 'Tapir', 'Cebra', 'Burro', 'Gatos', 'Perros', 'Mangosta', 'León', 'Leopardo', 'Guepardo', 'Jirafa', 'Okapi', 'Camello', 'Llama', 'Pacarí', 'Hipopótamo', 'Delfín', 'Ballenas', 'Cobayas', 'Elefante', 'Zorro', 'Panda', 'Mustélidos', 'Focas', 'Morsas', 'Elefante marino', 'Lobo marino', 'Mapache', 'Hiena', 'Musaraña', 'Conejo', 'Liebre', 'Ratón', 'Rata', 'Ornitorrinco', 'Erizo', 'Equidna', 'Zarigüeya', 'Ualabi', 'Perezoso', 'Armadillo', 'Oso hormiguero', 'Pangolín', 'Murciélago', 'Lémur', 'Tarsero', 'Simios', 'Macacos', 'Lobo', 'Dingo', 'Chacal', 'Nutria', 'Mofeta', 'Tejón', 'Zorrillo', 'Armiño', 'Comadreja', 'Marta', 'Oso marino ártico', 'Coatí', 'Civeta', 'Lince', 'Caracal', 'Ocelote', 'Manatí', 'Dugón', 'Rinoceronte', 'Cerdo hormiguero', 'Damán', 'Duiker', 'Ñu', 'Impala', 'Topi', 'Antílope', 'Gacela', 'Carnero', 'Muflón', 'Buey', 'Bongo', 'Bisonte', 'Yak', 'Gamo', 'Ciervo o venado', 'Guanaco', 'Vicuña', 'Jabalí', 'Pecarí', 'Narval', 'Baiji', 'Beluga', 'Orca', 'Marmota', 'Puercoespín', 'Ardilla', 'Castor', 'Capibara', 'Vizcacha']
// let flag = false;


// function pregunta(animal1) {

//     for (let i = 0; i < mamiferos.length; i++) {

//         if (animal1 == mamiferos[i]) {
//             flag = true;
//             alert(animal1 + " Si es un mamifero")

//         }
//     }

//     if (flag === false) {
//         alert("Tu animal no es un mamifero")

//         let animal = prompt("Elige un animal")
//         pregunta(animal);
//     } else {


//     }
//     return;
// }

// pregunta(animal)




// preguntar al usuario por un animal, determinar si el animal que nos a pasado es un mamifero o no


//--------------------------------------------------------------------function2-------------------------------------------------------

// let numero = prompt("Dime un numero")

// function divisible(numero) {

//, return numero;

// }

// if (numero % 3 == 0) {

//, document.write("Este numero es divisible por 3")

// } else {

//, document.write("Este numero no es divisible por 3")
// }





//Preguntar al usuario un numero si ese numero es divisible por 3, si lo es mensaje de este numero es divisible y no si este numero no es divisible

//---------------------------------------------------------------function1-------------------------------------------------------------------------

// let idioma = prompt("Cual es tu idioma?")
// let nombre = prompt("Cual es tu nombre?")


// function ingles(nombre) {
//, return "Hello "+ nombre;

// }

// function castellano(nombre) {
//, return "Hola "+ nombre;

// }

// function aleman(nombre) {
//, return "Hallo "+ nombre;

// }

// function elfico(nombre) {
//, return "Aiya "+ nombre;

// }


// switch (idioma) {
//, case "ingles":
//,, document.write(ingles(nombre))
//,, break;

//, case "castellano":
//,, document.write(castellano(nombre))
//,, break;

//, case "aleman":
//,, document.write(aleman(nombre))
//,, break;

//, case "elfico":
//,, document.write(elfico(nombre))
//,, break;


// }




//Preguntara al usuario por su idioma, (ingles,castellano, aleman o elfico) 
//Preguntar su nombre 
//mi funcion monstrara hola en su idioma y el nombre de la persona. -->



**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)