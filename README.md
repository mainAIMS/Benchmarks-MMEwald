# Benchmarks-MMEwald
The Benchmarks for MMEwald we port on the Sunway New Generation.

We can go to the directory which contains the control file (`control.in`) and the geometry file (`geometry.in`) , and perform the calculation.

We can submit the calculation to the queue using :

`bsub -b -m 1 -q <QUEUE_NAME> -n <nprocs> -cgsp 64 -share_size 13000 -priv_size 32 -host_stack 1024 FHI-aims.210402.scalapack.mpi`
