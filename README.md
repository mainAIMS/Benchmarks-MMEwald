# Benchmarks-MMEwald
The Benchmarks for MMEwald we port on the Sunway New Generation. This data includes example “RBD” data and "Si_core6" data of different cases with folder names like n_100_mini, n_100_rt_mini, et,al. 

We can go to the directory which contains the control file (`control.in`) and the geometry file (`geometry.in`) , and perform the calculation.

We can submit the calculation to the queue using :

`bsub -b -m 1 -q <QUEUE_NAME> -n <nprocs> -cgsp 64 -share_size 13000 -priv_size 32 -host_stack 1024 FHI-aims.210402.scalapack.mpi`
