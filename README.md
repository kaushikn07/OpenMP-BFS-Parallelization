# OpenMP BFS Parallelization
Paralleized BFS using the OpenMP library using the help of multithreading (4 Threads) and populating the frontier queues for each of the partitions using multithreading.

## How to run
Clone the repository and run the cpp file using the command
```
> g++ -fopenmp parallelizedBFS.cpp -o run.exe
> ./run.exe
```

## Libraries used
>* OpenMP (#include <omp.h>)
>* STL Library (#include <bits/stdc++.h>)

