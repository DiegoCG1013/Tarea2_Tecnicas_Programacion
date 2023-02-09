# Tarea_2_Tecnicas_Programacion

Tarea 2 Curso_22_23_Tecnicas

# Mi repositorio: 
* https://github.com/DiegoCG1013/Tarea2_Tecnicas_Programacion.git

# Ejercicios:

## 1. Valores de las variables
¿Cuáles serán los valores de las variables a y b después de cada línea del siguiente algoritmo?

Algo ValoresDeLasVariables  
variable a, b: entero  
Inicio  
   Linea de codigo | Valor a | Valor b
   -- | - | -
   a <- 3  | 3 | Null // 0 (Depende del lenguaje)
   escribir("a = " & a) | 3 | Null // 0 (Depende del lenguaje)
   b<-a+5 | 3 | 8
   escribir("a = " & a & " y b = " & b) | 3 | 8
   a<-7 | 7 | 8
   escribir("a = " & a & " y b = " & b)  | 7 | 8
Fin  

## 2. ¿Qué se muestra?
¿Qué veremos al ejecutar el siguiente algoritmo?

Algo QueVeremos 
- ¿Qué veremos al ejecutar el siguiente algoritmo?  
Variable valor1, valor2: entero  
Variable cadena1: texto  
Constante CST: real <- 49,78  
Inicio  
   valor1 <- 92 % 8  
   valor2 <- 2 * valor1  
   cadena1 <- "Test"  
   escribir(cadena1 & " , valor2 = " & valor2)  
   escribir(valor1 & " # " & CST)  
Fin 

### Respuesta: 
> Exactamente se mostrará lo siguiente: 
> "Test , valor2 = 8"
> "4 # 49,78"

## 3. ¿Qué hace?
¿Qué hace este algoritmo?

Algo QueHace  
- ¿Qué hace este algoritmo?  
Variable valor1, valor2: real  
Inicio  
   valor1 <- enter("Introduza un valor: ")  
   valor2 <- enter("Introduza otro valor: ")  
   - tratamiento 
   valor1 <- valor2  
   valor2 <- valor1  
   escribir("valor1 = " & valor1 & "; valor2 = " & valor2)  
Fin 

### Respuesta:
> Este algoritmo mostraria lo siguiente por pantalla: "valor1 = (Segundo valor introducido por el usuario); valor2 = (Segundo valor introducido por el usuario)"

## 4. Velocidad media
Escriba un algoritmo que calcule la velocidad media de desplazamiento del usuario.

A continuación, se muestra un ejemplo de posibles visualizaciones y entradas durante una ejecución del algoritmo (los valores introducidos por el usuario están escritos en negrita y cursiva):

Introduzca la distancia recorrida (km).

370

Introduzca el tiempo del recorrido (min).

240

Se ha desplazado a una velocidad de 92,5 km/h.

### Respuesta: 
> **distancia, tiempo: real** 
>
> **distancia <- enter("Introduzca la distancia recorrida (km).")**
>
> **tiempo <- enter(Introduzca el tiempo del recorrido (min).)**
>
> **escribir("Se ha desplazado a una velocidad de " & (distancia/(tiempo/60)) & " km/s")**