# Introduction
This repository contains samples authored by NVIDIA for OpenCL. A complete list of samples can be found on the official [page](https://developer.nvidia.com/opencl). Unfortunately, the samples posted on that page do not build cleanly and therefore this repository. 

The repo currently includes the following samples:
1. oclDeviceQuery
1. oclBandwidthTest
1. oclVectorAdd 

# Usage
To get started, first install the OpenCL ICD loader:
```bash
$ apt-get install -y ocl-icd-opencl-dev
```

Then, clone this git repo and build the samples:

```bash
$ cd OpenCL \
   && make 
```

This will result in the binaries for all the samples located in the `OpenCL/bin` directory.
