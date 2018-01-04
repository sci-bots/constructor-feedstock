About constructor
=================

Home: http://github.com/conda/constructor

Package license: BSD 3-Clause

Feedstock license: BSD 3-Clause

Summary: create installer from conda packages



Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/constructor-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/constructor-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/constructor-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/constructor-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/constructor-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/constructor-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/sci-bots/constructor/badges/version.svg)](https://anaconda.org/sci-bots/constructor)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/sci-bots/constructor/badges/downloads.svg)](https://anaconda.org/sci-bots/constructor)

Installing constructor
======================

Installing `constructor` from the `sci-bots` channel can be achieved by adding `sci-bots` to your channels with:

```
conda config --add channels sci-bots
```

Once the `sci-bots` channel has been enabled, `constructor` can be installed with:

```
conda install constructor
```

It is possible to list all of the versions of `constructor` available on your platform with:

```
conda search constructor --channel sci-bots
```




Updating constructor-feedstock
==============================

If you would like to improve the constructor recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`sci-bots` channel, whereupon the built conda packages will be available for
everybody to install and use from the `sci-bots` channel.
Note that all branches in the conda-forge/constructor-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.