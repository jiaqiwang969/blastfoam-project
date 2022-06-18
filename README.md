# blastfoam-project
Aim: High resolution fvm simulation using [blastfoam](https://github.com/synthetik-technologies/blastfoam) scheme 

### Installation
```
mv Dockerfile.step01 Dockerfile
docker build jiaqiknight/openfoam-blastfoam:v1 .
mv Dockerfile.step02 Dockerfile
docker build jiaqiknight/openfoam-blastfoam:v2 .
singularity build openfoam-blastfoam-v2012.sif Singularity-openfoam.def
singularity shell openfoam-blastfoam-v2012.sif
```

### Use Action to dockerhub
