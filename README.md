# Twilight
#Codigo Swift

import Foundation
var palabra: String
var cadena1 = "Hola!!!"
var cadena2 = "Sayounara"
var cadena3 = cadena1 + " " + cadena2
for char in cadena1.characters{
	print (char)
}

print(cadena3)
palabra = "estoy vivoooo.... "
print (palabra)


var nombre = "Lenne"
var result = "Soy \(nombre) y estoy feliz :) "
 
print (result)
////
var x = "Hola"
let y = "Quihubos"
var z = "mundo"

x += z // concatena cadenas
print(x)

//y += z no se puede pues "y" no es murtable 

print (cadena1.lowercased( )) //imprime la cadena en minusculas
print (cadena2.uppercased( )) //imprime la cadena en mayúsculas 

var cadena = "" 
print (cadena.isEmpty) //.isEmpty es una propiedad que indica si la variable esta vacía o no

print(cadena1.hasPrefix("Hola"))
print(cadena1.hasSuffix("Hola"))

var mensaje = "Mis alumnos van a aprobar"
print (mensaje.replacingOccurrences(of:"aprobar", with: "reprobar"))
