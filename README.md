# singularity-docker-centos8-brave
centos8 container to run brave (at library://tru/default/c8-brave)


Running without installation:
```
singularity run  -B /run library://tru/default/c8-brave
```
Building:
```
sudo singularity build singularity-docker-centos8-brave.sif  Singularity
```
Download and rename:
```
singularity pull --name singularity-docker-centos8-brave.sif library://tru/default/c8-brave
```
Running with a separate $HOME  (here ~/singularity.d/home/singularity-docker-centos8-brave)
```
mkdir -p  ~/singularity.d/home/singularity-docker-centos8-brave
singularity run  -B /run  -H ~/singularity.d/home/singularity-docker-centos8-brave singularity-docker-centos8-brave.sif
```
