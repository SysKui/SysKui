# Overview

SysKui is a system used to automate the execution of fault injections and to verify and evaluate the fault tolerance mechanism of the operating system

## Submodules

### lava

The lava submodule stores the source code of the LAVA automated test cluster, which we use to build the image to be used by lava-docker

### lava-docker

lava-docker is the repository we use to generate docker-compose.yml configuration files and then create lava container clusters

### flip_simualtion

The flip-simulation repository has the GDB scripts used by the Lava automated testing framework for fault injection
