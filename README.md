 # EJERCICIOS PRÁCTICOS CLASE N°1

### 1. Ejercicio de Descomposición

Problema: Hacer panqueques

1. En un recipiente, mezclar la harina, azúcar, sal, agua o leche.
2. Batir hasta obtener una mezcla homogénea.
3. Calentar la sartén a fuego lento.
4. Agregar mantequilla.
5. Verter la mezcla en la sartén.
6. Cuando aparezcan burbujas, cocinar el otro lado.


### 2. Ejercicio de Abstracción

Un semáforo utiliza 3 colores para regular el tráfico. Estos indican cuándo el conductor debe reducir su velocidad, detenerse o pasar. El semáforo cambia de color después de cierto tiempo para adaptarse al flujo de tráfico.

Los colores significan lo siguiente:

- Rojo: Parar.
- Amarillo: Disminuir velocidad.
- Verde: Seguir.


### 3. Diagrama de Flujo
![a6500c5d-c4a3-4466-9766-6303bec117c9](https://github.com/user-attachments/assets/027400f7-d19e-4b53-aae9-8514b617abe8)




### 4. Ejercicios de Patrones


lista:3,6,12,24,48,96


- cada uno es el doble del anterior por lo tanto es una progresion geometrica con razon de 2
- 3*2=6
- 6*2=12
- 12*2=24
- 24*2=48
- 48*2=96









# Ejercicios Prácticos - Clase N°2

### 1. Pseudocódigo

Algoritmo para determinar si un número es par o impar

```
ALGORITMO determinar_par_impar
INICIO
ESCRIBIR "Ingrese un número:"
 LEER numero
SI numero MOD 2 == 0 ENTONCES
  ESCRIBIR "El número es par."
SINO ESCRIBIR "El número no es par."
FIN SI
FIN
  ```
### 2. diagrama de flujo




![8b22d859-cf2c-4d91-8529-b598f9c8acd0](https://github.com/user-attachments/assets/a66c2a55-0185-4e64-a128-af1373bdab45)







  # 4.Implementar en pseudocódigo un algoritmo que calcule el factorial de un numero
```
  
ALGORITMO calcular_factorial
  INICIO
   LEER numero
factorial = 1
PARA i DESDE 1 HASTA numero HACER
factorial = factorial * i
FIN PARA
ESCRIBIR "El factoriar de" numero  "es:" factorial
FIN
````
# CLASE Nº3 EJERCICIOS PRACTICOS 

### 1. Declara una variable para almacenar la edad de una persona y asigna un valor.

- DEFINIR edad COMOENTERO edad <-18

### 2. scribe una expresión que combine operadores aritméticos y relacionales.
- resultado <-(10+5)*2 > 20 = // resultado = false
### 3.nvierte el número decimal 13 a binario.
- 13/2 cociente 6 residuo 1 
- 6/2 cociente 3 residuo 0
- 3/2 cociente 1 residuo 1
- 1/2 cociente 0 residuo 1
- por lo tanto 13 en binario seria 1101
### 4.Escribe una expresión que utilice operadores lógicos para verificar si un número está entre 10 y 20.
````
DEFINR numero COMO ENTERO
NUMERO <- 18
estaenrango<-(numero>=10) y (numero <=20) // resultado = true 

`````
# CLASE Nº4  EJERCICOS PRACTICOS 
 ### 1.Escribe un algoritmo en PSeInt que solicite el nombre de un usuario y lo salude.
 ````
ALGORITMO hola_usuario
DEFINIR usuario como cadena
ESCRIBIR"Ingrese su usuario"
LEER usuario
ESCRIBIR"¡HOLA" usuario
FINALGORITMO
 ````
### 2.Crea un programa que pida un número y valide que sea positivo.

````
ALGORITMO ValidarNumeroPositivo  
DEFINIR numero COMO REAL  
// Pedir un número al usuario
REPETIR  
ESCRIBIR "Ingrese un número positivo:"  
LEER numero       
 // Verificar si el número es negativo o cero
SI numero <= 0 ENTONCES  
 ESCRIBIR "Error: El número debe ser positivo. Inténtelo nuevamente."  
       FIN SI  
   HASTA QUE numero > 0  
   // Mostrar el número válido
   ESCRIBIR "Número válido ingresado:", numero  
FIN ALGORITMO
````
### 3.Desarrolla un algoritmo que solicite tres números y muestre la suma de ellos.
````
ALGORITMO sumadetresnumeros  
DEFINIR num1, num2, num3, suma COMO REAL  
// Solicitar los números al usuario
ESCRIBIR "Ingrese el primer número:"  
LEER num1  
ESCRIBIR "Ingrese el segundo número:"  
  LEER num2  
ESCRIBIR "Ingrese el tercer número:"  
   LEER num3  
   // Calcular la suma
   suma <- num1 + num2 + num3  
   // Mostrar el resultado
   ESCRIBIR "La suma de los tres números es:" suma  
FIN ALGORITMO
````
### 4.Implementa una solución que pida la edad de una persona y solo la acepte si es mayor a 0.
````
ALGORITMO ValidarEdad  
DEFINIR edad COMO ENTERO  
  // Pedir la edad al usuario y validar que sea mayor a 0
 REPETIR  
  ESCRIBIR "Ingrese su edad (debe ser mayor a 0):"  
    LEER edad  
       // Verificar si la edad es inválida
     SI edad <= 0 ENTONCES  
    ESCRIBIR "Error: La edad debe ser un número mayor a 0. Intente de nuevo."  
     FIN SI  
   HASTA QUE edad > 0  
   // Mostrar la edad válida
   ESCRIBIR "Edad válida ingresada:", edad 
   FINALGORITMO
````
