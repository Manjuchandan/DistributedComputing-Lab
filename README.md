# DistributedComputing-Lab

Commands to run Openmp programs.
1) gcc -fopenmp <filename.c>
2) ./a.out

Commands to run Mpi programs.
1) mpicc <filename.c>
2) mpirun -np 4 ./a.out 

Note : For 3rd , 5th and 9th programs we have to link math library
so commands will altered as,
gcc -fopenmp <filename.c> -lm
mpicc <filename.c> -lm
