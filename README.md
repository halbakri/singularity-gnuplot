![Status](https://github.com/pscedu/singularity-gnuplot/actions/workflows/main.yml/badge.svg)
![Issue](https://img.shields.io/github/issues/pscedu/singularity-gnuplot)
![forks](https://img.shields.io/github/forks/pscedu/singularity-gnuplot)
![Stars](https://img.shields.io/github/stars/pscedu/singularity-gnuplot)
![License](https://img.shields.io/github/license/pscedu/singularity-gnuplot)

# singularity-gnuplot
![Plot](http://gnuplot.info/figs/gaussians.png)

Singularity recipe for [gnuplot](http://gnuplot.info/).

## Installing the container on Bridges 2
Copy the

* `SIF` file
* and the `gnuplot` script

to `/opt/packages/gnuplot/5.4`.

Copy the file `modulefile.lua` to `/opt/modulefiles/gnuplot` as `5.4.lua`.

## Building the image using the recipe
### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

## To run tests
To run the available tests, run the command

```
bash ./test.sh
```

---
Copyright © 2020-2021 Pittsburgh Supercomputing Center. All Rights Reserved.

The [Biomedical Applications Group](https://www.psc.edu/biomedical-applications/) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in the [Mellon College of Science](https://www.cmu.edu/mcs/) at [Carnegie Mellon University](http://www.cmu.edu).
