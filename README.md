About fftw-mpi
==============

Home: http://fftw.org

Package license: GPL 2

Feedstock license: BSD 3-Clause

Summary: The fastest Fourier transform in the west.



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/cryoem/fftw-mpi-feedstock.svg?style=shield)](https://circleci.com/gh/cryoem/fftw-mpi-feedstock)
OSX: [![TravisCI](https://travis-ci.org/cryoem/fftw-mpi-feedstock.svg?branch=master)](https://travis-ci.org/cryoem/fftw-mpi-feedstock)
Windows: ![](https://cdn.rawgit.com/conda-forge/conda-smithy/90845bba35bec53edac7a16638aa4d77217a3713/conda_smithy/static/disabled.svg)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/cryoem/fftw-mpi/badges/version.svg)](https://anaconda.org/cryoem/fftw-mpi)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/cryoem/fftw-mpi/badges/downloads.svg)](https://anaconda.org/cryoem/fftw-mpi)

Installing fftw-mpi
===================

Installing `fftw-mpi` from the `cryoem` channel can be achieved by adding `cryoem` to your channels with:

```
conda config --add channels cryoem
```

Once the `cryoem` channel has been enabled, `fftw-mpi` can be installed with:

```
conda install fftw-mpi
```

It is possible to list all of the versions of `fftw-mpi` available on your platform with:

```
conda search fftw-mpi --channel cryoem
```




Updating fftw-mpi-feedstock
===========================

If you would like to improve the fftw-mpi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cryoem` channel.
Note that all branches in the cryoem/fftw-mpi-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
