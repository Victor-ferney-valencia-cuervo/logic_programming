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

```plaintext
ALGORITMO determinar_par_impar
INICIO
    ESCRIBIR "Ingrese un número:"
    LEER numero
    SI numero MOD 2 == 0 ENTONCES
        ESCRIBIR "El número es par."
    SINO
        ESCRIBIR "El número no es par."
    FIN SI
FIN
  ```
### 2. diagrama de flujo




![8b22d859-cf2c-4d91-8529-b598f9c8acd0](https://github.com/user-attachments/assets/a66c2a55-0185-4e64-a128-af1373bdab45)


### 3.Analizar eficiencia de Algoritmos

### 1.busqueda secuensial en una lista
- es practicamente recorrer una listade inicio a fin
- en el peor caso se debe  recorrer toda la lista para encontrar el elemento
  ### analisis

 
- Tiempo de Ejecucion o(n) el elemento esta al inicio , o(n) se revisan todos los elementos
- espacio en memoria o(1)

  ### 2.ordenamiento por burbuja
  -se compara cada elemonto con los demas e intercambian elementos hasta que la lista este ordenada 
  ### analisis

- Tiempo de Ejecucion o(n) para cuando la lista de elementos este ordenada , o(n^2)la lista esta invertida
- espaci de memoria  o(1)
    

  ### 3.busqueda vinaria de array ordenado
  -se divide la lista a la mitad en cada  paso descartando la mitad donde no esta el elemento
  ### analisis
  - Tiempo de Ejecucion o(1) el elemento esta en el medio , o(log n ) se reducen las comparaciones dividiendo la lista en mitades
  - espacio de memoria o(1) usando solo unas pocas variables 


  
