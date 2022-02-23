*VARIABLES
Las Variables son datos o valores (informacion) almacenados dentro del codigo que podrian usarse nuevamente en
caso de que se requiera. Se denominan 'Variables' porque sus valores almacenados previamente pueden 
modificarse, es decir, pueden variar.
Las variables deben declarasse mediante una palabra clave denominada "var" (se debe escribir SIEMPRE en 
MIUNUSCULA), posteriormente, definir el nombre de esta y por ultimo indicar su valor con el signo '='.
Ejemplos de variables:
var name = "Juan";
var num = 2;
 

 *STRINGS
 "String" es una palabra inglesa que significa 'cadena' en español, las "strings" dentro del ambito de la
 programacion son cadenas o bloques de caracteres. Siempre se debe colocar la "string" dentro de dos comillas,
 ya sean dobles ("") o simples ('').
Ejemplos de las "strings".
var nombre = "Juan" //correcto
var nombre = 'Juan' //correcto
var nombre = Juan // incorrecto






*FUNCTIONS
Las "functions" (o funciones en español) son bloques de codigo creados para cumplir una tarea en especifica.
Las "functions" suelen llevar el nombre de la tarea a cumplir, para que la tarea se lleve a cabo hay que 
llamarla/invocarla. Las "functions" pueden llamarse atraves de un click por el usuario o atraves del codigo
dentro de JavaScript. Las "functions" son muy importantes dentro de JavaScript ya que pueden utulizarse cuantas
veces se requiera.
Una "function" se declara de la siguiente manera:
function myFisrtFunction ()
{
    //aca va el codigo
}

myFirstFunction ()

Dentro de los parentesis le asignaremos el paramentro a cumplir, es decir, un argumento. El argumento es el
valor que nos devolvera la "function" cuando la 'llamenos' utilizando palabra clave "return". Los argumentos
se comportan como variables locales dentro de la "function".

function saludar()
{
    console.log("hola")
}

saludar();





*DECLARACIONES
Los condicionales son bloques de codigo que se ejecutan mediante un operador de control de flujo y comparacion 
Los operadores mas comunes son "if", "else" y "else if", estos nos permitiran verificar el resultado de 
nuestro  codigo, es decir, si una condicion se esta cumpliendo (o no) y nos devolvera un valor. Nuestro codigo 
se terminara de ejecutar cuando se alcance alresultado.
Generalmente los condicionales llevan como respuesta un operado logico, es decir, un booleano (true o false).

if (esta condicion se cumple)
{
    se ejecutara este codigo;
}
else
{
    este codigo;
}
}



if (edad > 18)
{
    return true;
}
else
{
    return false;
}
}

edad(22);

El codigo se ejecutara y se detendra cuando la primera condicion se cumpla, es este caso es "true".
Los "booleanos" son valores que actuan segun 'la logica de boole' y nos dan un resultado logico.







