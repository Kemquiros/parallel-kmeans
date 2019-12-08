# K-means paralelo con OpenMP

### Compilar
clear && gcc -o kmeans -fopenmp -lm kmeans.c

### Variables de entorno
export OMP_NUM_THREADS=4

### Ejecutar
./kmeans -c 6 -i 8 -a datos_muestra_2.txt

### Parametros
#### c: número de centroides
#### i: número máximo de iteraciones
#### a: archivo de entrada