Nota:
=====
Este documento irá cambiando conforme evolucione el curso. Organizaremos el temario
por clases y lo adaptaremos a medida que vayamos avanzando.

Objetivos: 
==========
* Conocer algunas herramientas de programación eficientes y modernas (julia,
  git y Travis CI) para poder atacar problemas actuales. 
* Aprender a usar git para _colaborar_ de manera eficiente.
* Saber como se piensa cuando se hace investigación, es decir de manera no
  lineal y sin un camino claro. 
* Aprender elementos de información cuántica.


Temario (16 semanas):
=====================
1. Introduccion, plan general y evaluación.
   * Instalación de git 

   Introducción al curso: temario, evaluación y objetivos.
   Se comentará en general el estilo de trabajo para el curso.
1. Git
   * Comandos basicos: add, commit, push, pull y clone.
   * Pull request y merging.
[//]: # ( * Propongo que en esta clase todos comiencen con su libreria, que hagan una cuenta y clonen el repositorio y agreguen por lo menos un primer commit. )
[//]: # ( * Aqui Luis y David hicieron un primer ejemplo de libreria, todos hicimos git fork y comenzamos a contribuir solicitando pull request a la copia principal.)
1. Julia (diagonalizacion, hablar de RMT, o del mapeo logistico)
   * Sintaxis
   * Jupyper-notebook
     * Markdown
     * Yo uso la version de anaconda, esta bien mantenida.
   * Librerias: Llamar y hacer
   * Usar \textit{static type}, Amaro dice que es la forma de sacarle jugo a Julia.
   * Definir funciones
   * Operadores logicos
   * Loops: definir bien el conteo de los elementos del estado.
   * Benchmarking (tic() tac()): Memoria y CPU.
   * Estandarización de objetos.
1. Julia (dibujos y ejemplos bonitos, optica cuantica)
1. Julia (bitwise operations, loops, )
1. CI Travis 
1. Qutip?
   * Clase de qutip, esta seria con una pequeña introduccion a python.
1. Benchmark velocidad y memoria en Julia
******
1. Sistemas de 1 qubit, esfera de Bloch, numeración en sistemas
   de n qubits. 
   * Hadamard
   * Estados aleatorios en una dimension y en n dimensiones
   * Compuertas de pauli
   * Compuertas de 1 qubit: $\hat O=\mathbb{1}+ \vec v \cdot \vec \sigma$, ver
     rotaciones en la esfera de Bloch
1. Traza parcial, programación de traza parcial y significado físico de la traza.
   Estados enredados, valores esperados en estados de Bell. 
   * qubits en general
   * sistemas bipartitos con dimensión arbitraria factorizable.
1. Estados de n qubits y compuertas de un qubit, tomografia
   * Estados de $N$ qubits: Separables y enredados, definición estándar del objeto en Julia.
   * Compuertas de 2 qubits: CNOT, $\sigma^z \sigma^z}$
   * modelo XYZ
   * Tomografía de un qubit
   * Decoherencia Explicar un poco de spin flip, phase flip, etc.
1. Compuertas de dos qubits y algun ejemplo, entaglement swaping?
1. Concatenacion de compuertas, cadena con un defecto. (ver con carlos gonzales) 

Quiza en las cosas introductorias de Julia, poner algo de RMT. Quiza la P(s). 

Uno de los proyectos, puede ser construir la base simetrica para la cadena

Lista de ejemplos para estudiar a medida que aprendemos Julia
=============================================================
* Entanglement swaping 
* Nearest neighbour spacing (GUE, GOE y aleatoria)
* Tomografía cuántica

Algunas alternativas para proyectos finales
===========================================

* _Teoría de matrices aleatorias_-
  Estudiar numéricamente las propiedades espectrales de matrices aleatorias y
  compararlas con un espectro de una cadena inhomogénea.
* _Simular el algoritmo de Shor_-
* _Simular cluster quantum computing_-
* _Alguna alternativa propuesta por ustedes_- 
  Pueden proponer un proyecto, pero este debe ser aceptado. Debe tener un
  objetivo claro y debe hacer uso de algunas herramientas propuestas en clase.
* _Una base simetrica para la cadena de Ising_- 
  Estudiar la cadena de Ising y constuir una base que sea consistente con dicha
  simetría.
* Rompimiento de simetria y caos cuantico: Trabajo de Carlos.
* ambientes anidados
\item Transformada cuantica de fourier
\item Que tal que implementen todo el asunto de representaciones de canales cuanticos y operaciones importantes como Reshuffling y esas cosas.
\item Cosas de variable continua tipo qutip.
