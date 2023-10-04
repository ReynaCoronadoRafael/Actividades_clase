# Actividades_clase
// 2. Volver flotante a la variable decimal
val numeroFlotante = numeroDecimal.toFloat()
println("La variable decimal convertida a flotante es: $numeroFlotante")

// 3. Declarar una variable const val con el valor de Pi y multiplicarla por 2 veces nuestra variable decimal para sacar el perímetro de un círculo.
val Pi: Double = 3.141592
val radio = numeroDecimal
val perimetro = 2 * Pi * radio

// a. Utilizar un String Template para imprimir el texto "El perímetro del círculo es: [resultado]" siendo resultado nuestra variable perímetro.
println("El perímetro del círculo es: $perimetro")

fun main() { val numeros = mutableList0f("one","two","three","four","five","four","four") val numSet: Set = set0f(0, 1, 2, 3, 4, 5, 5) println("Numero de elementos: {numeros.get(1)}") println("Cuarto elemento:

{numeros.get(numeros.size - 1)}") println("Index del elemento "four": ${numeros.index0f("four")}")

}

)
for (nombre in nombres){
    println(nombre)
    if (nombre=="Link"){
        println("Personaje Encontrado!")
        break
    }
}

fun login(user: String, password: String): Boolean { fun validate (input: String): Boolean{ if (input.isEmpty()){ return false } return true } val userValidated = validate(user) val passValidated = validate(password)

return userValidated && passValidated

}

fun main(){ val base = 20f val altura = 4f val area = areaRectangulo(base,altura) println("el area del rectangulo es $area") } fun areaRectangulo(base: Float, altura: Float):Float{ return base*altura }

Área de un circulo

import kotlin.math.PI

fun main() { // Define el radio del círculo val radio = 5.0

// Calcula el área del círculo
val area = PI * radio * radio

// Imprime el resultado
println("El área del círculo con radio $radio es: $area")

}

Operadores if y when

package com.example.myapplication

fun main(){ //verifAge() //gradoEscolar() //GradoEscolar()

} fun verifAge(){ print ("Ingrese edad y precione enter(escribe solo el numero):") val age = readLine()?.toInt()

if(age==18){ println("Ya eres mayor de edad¡") } if(age!! >18){ println("Ya eres mayor de edad") } else if (age!! == 18){ println("Acabas de cumplir la mayoria de edad")

} else{ println("Eres menor de edad") }
