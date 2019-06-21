# R2jags-image

A Singularity recipe for an R container with JAGS and OpenBUGS packages.

JAGS 4 comes from Ubuntu repo, and OpenBUGS is built from the sources which are downloaded from http://pj.freefaculty.org/Ubuntu/15.04/amd64/openbugs/ 

## Usage

Usually you'd want to pull the container from Singularity-Hub. Assuming you have Singularity runtime installed:

singularity pull shub://gshamov/R2jags-image

