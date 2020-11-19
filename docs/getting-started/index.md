# Getting Started

This section describes some of the example MLCommon-Box cubes, in particular it covers the following topics:

- Setting up python environment.
- Running simple MLCommon-Box cubes.
- Detailed description of the internal structure of MLCube cubes.


## Repository of MLCube examples.
MLCommons hosts a simple GitHub-based repository with example MLCube cubes. It is located [here](https://github.com/mlperf/cube_examples).


## Setting-up python environment
In various tutorials we start with setting up Python environment and downloading MLCube cubes. Here is the step by step guide:
```
# Clone MLCube Examples
git clone https://github.com/mlperf/cube_examples.git && cd ./cube_examples

# Create Python Virtual Environment
virtualenv -p python3 ./env && source ./env/bin/activate

# Install MLCube Docker runner 
pip install mlcube-docker

# Optionally, setup host environment by providing the correct `http_proxy` and `https_proxy` environmental variables.
# export http_proxy=...
# export https_proxy=..

# Optionally, install other runners
# pip install mlcube-singularity
# pip install mlcube-ssh
``` 