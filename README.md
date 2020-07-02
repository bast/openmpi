

# Singularity recipe for OpenMPI

https://singularity-hub.org/collections/4519

```
$ singularity pull --name openmpi.sif shub://bast/openmpi:4.0.4-gcc-9.3.0
$ singularity exec openmpi.sif mpicc example.c
$ singularity exec openmpi.sif mpirun -n 4 ./a.out
```
