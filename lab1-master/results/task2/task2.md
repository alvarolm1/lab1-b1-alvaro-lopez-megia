# Task 2:

-- **Una vez realizado el survey en la parte de arriba debería observarse un warning, ¿Qué es lo que indica este aviso? ¿Como solucionarías este problema de modo que el warning desaparezca?**

El error mostrado es:

![](https://github.com/alvarolm1/lab1-b1-alvaro-lopez-megia/blob/main/lab1-master/results/task2/WARNING.png)

Lo que causa este error es el compilador que hemos usado (g++):

 `g++ -g -fopenmp -O0 matmul.cpp`
 
 La solución sería utilizar un compilador de Intel, como es:

`{icx|icpx} [options] file1 [file2...]  ` 
