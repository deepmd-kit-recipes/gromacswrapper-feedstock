About gromacswrapper
====================

Home: https://github.com/Becksteinlab/GromacsWrapper

Package license: GPL-3.0

Feedstock license: [BSD-3-Clause](https://github.com/deepmd-kit-recipes/gromacswrapper-feedstock/blob/master/LICENSE.txt)

Summary: A python wrapper around the Gromacs tools.

Documentation: https://pythonhosted.org/GromacsWrapper/

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/gromacswrapper-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gromacswrapper-green.svg)](https://anaconda.org/deepmodeling/gromacswrapper) | [![Conda Downloads](https://img.shields.io/conda/dn/deepmodeling/gromacswrapper.svg)](https://anaconda.org/deepmodeling/gromacswrapper) | [![Conda Version](https://img.shields.io/conda/vn/deepmodeling/gromacswrapper.svg)](https://anaconda.org/deepmodeling/gromacswrapper) | [![Conda Platforms](https://img.shields.io/conda/pn/deepmodeling/gromacswrapper.svg)](https://anaconda.org/deepmodeling/gromacswrapper) |

Installing gromacswrapper
=========================

Installing `gromacswrapper` from the `deepmodeling` channel can be achieved by adding `deepmodeling` to your channels with:

```
conda config --add channels deepmodeling
conda config --set channel_priority strict
```

Once the `deepmodeling` channel has been enabled, `gromacswrapper` can be installed with `conda`:

```
conda install gromacswrapper
```

or with `mamba`:

```
mamba install gromacswrapper
```

It is possible to list all of the versions of `gromacswrapper` available on your platform with `conda`:

```
conda search gromacswrapper --channel deepmodeling
```

or with `mamba`:

```
mamba search gromacswrapper --channel deepmodeling
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search gromacswrapper --channel deepmodeling

# List packages depending on `gromacswrapper`:
mamba repoquery whoneeds gromacswrapper --channel deepmodeling

# List dependencies of `gromacswrapper`:
mamba repoquery depends gromacswrapper --channel deepmodeling
```




Updating gromacswrapper-feedstock
=================================

If you would like to improve the gromacswrapper recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`deepmodeling` channel, whereupon the built conda packages will be available for
everybody to install and use from the `deepmodeling` channel.
Note that all branches in the deepmd-kit-recipes/gromacswrapper-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@AnguseZhang](https://github.com/AnguseZhang/)
* [@felix5572](https://github.com/felix5572/)

