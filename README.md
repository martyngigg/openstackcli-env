# Openstack Conda Environment

Stores configuration of a Conda-based Python environment with the openstacksdk
and various additional tools configured.
It is indended for accessing the Openstack CLI without having to pollute any
global Python installation with the necessary tools.

## Create the environment

Assuming `conda` is installed run (from this directory):

```sh
conda env create -f ./condaenv
```

