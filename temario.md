Nota:
=====
Este documento irá cambiando conforme evolucione el curso. Organizaremos el temario
por clases y lo adaptaremos a medida que vayamos avanzando.

Objetivos: 
==========
* Conocer algunas herramientas de programación eficientes y modernas (Julia,
  git y Travis CI) para poder atacar problemas actuales. 
  * Aprender a usar git para _colaborar_ de manera eficiente.
  * Aprender a usar julia para _calcular_ y visualizar datos.
  * Usar Travis CI para controlar que nuestro código.
* Aprender elementos de información cuántica.
* Saber como se piensa cuando se hace investigación, es decir de manera no
  lineal y sin una meta 100% bien definida.


Temario (16 semanas):
=====================
1. Introduccion, plan general y evaluación.
   * Instalación de git 
   Introducción al curso: temario, evaluación y objetivos.
   Se comentará en general el estilo de trabajo para el curso.
2. Git básico
   * Algunos comandos: add, commit, push, pull y clone.
   * Autenticación automatica 
   * Pull request y merging.
[//]: # ( * Propongo que en esta clase todos comiencen con su libreria, que hagan una cuenta y clonen el repositorio y agreguen por lo menos un primer commit. )
[//]: # ( * Aqui Luis y David hicieron un primer ejemplo de libreria, todos hicimos git fork y comenzamos a contribuir solicitando pull request a la copia principal.)
3. Julia, una introducción rápida
   * Sintaxis
   * Jupyper-notebook
     * Markdown
   * Definir funciones
   * Operadores logicos
   * Loops: definir bien el conteo de los elementos del estado.
4. Git avanzado
5. Travis CI
6. Estados aleatorios y algebra lineal básica en Julia, qubits, esfera de Bloch, matriz de densidad 1, matrices de Pauli
7. Sistemas compuestos, teleportacion, librerias en Julia, matriz de densidad II, traza parcial. Estados separables y enredados, programación de traza parcial y significado físico de la traza, estados de Bell
8. Sistemas de muchos qubits, representacion. Operaciondes de uno y dos qubits. Bitwise operacions
9. Ejemplos I: la transformada cuantica de Fourier. Compuerta Hadamard, phase gate, 
   controlled phase. Funciones anónimas.
   * Concatenacion de compuertas
   * Cadena con un defecto. 
10. Ejemplo II: matrices aleatorias y la cadena de Ising

Posibles temas a tratar en futuras iteraciones del curso
========================================================
* Entanglement swaping 
* Nearest neighbour spacing (GUE, GOE y aleatoria)
* Tomografía cuántica
* Cosas de variable continua tipo qutip.
* Benchmarking (tic() tac()): Memoria y CPU y comandos @
* _static type_, o como sacarle jugo a Julia.

Algunas alternativas para proyectos finales
===========================================

* _Teoría de matrices aleatorias_- Estudiar numéricamente las propiedades
  espectrales de matrices aleatorias y
  compararlas con un espectro de una cadena inhomogénea. Se pedirán las usuales que aparecen en el libro de Mehta. 
* _Simular el algoritmo de Shor_- Se realizará un estudio numérico de como
  factorizar números usando la QFT. 
* _Una base simetrica para la cadena de Ising_- Estudiar la cadena de Ising y
  constuir una base que sea consistente con dicha
  simetría. Se deberá poder diagonalizar el sistema por bloques y que den 
* Estudiar profundamente la cadena de Ising con un defecto. Probar las
  diferentes simetrias y obtener GOE y GUE. Ver la transición,
 incluyendo los factores de forma, con sistemas optimizados.
* Implmementar un toolkit para la representacion de canales cuanticos,
  isomorfismo de Jamiolkowski, etc.
* Jugar con https://github.com/JuliaQuantum y hacer un Jaynes–Cummings. 
* Estudiar la Integrated Information (ver charla en CCS2016 de Pedro) en
  cadenas de espin. Posibles configuraciones: una sola cadena
  caotica/integrable, dos cadenas, una integrable y otra caotica o dos
  caoticas, sistema de qubit y ambiente, o qubit y dos ambientes.
* Tomografía de varios qubits, costo computacional y compressed sensing
* _Benchmarking de nuestas rutinas_ La idea es hacer un benchmarking en serio, y comparar el 
  desempeño de lo desarrollado aca con rutinas uqe tenemos en fortran, c++ y python.

