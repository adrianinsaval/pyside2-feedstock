About pyside2-feedstock
=======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/pyside2-feedstock/blob/main/LICENSE.txt)

Home: https://wiki.qt.io/PySide2

Package license: LGPL-3.0-only

Summary: Python bindings for Qt

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_python3.11.____cpython</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=4150&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/pyside2-feedstock?branchName=main&jobName=win&configuration=win%20win_64_python3.11.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyside2-green.svg)](https://anaconda.org/freecad/pyside2) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/pyside2.svg)](https://anaconda.org/freecad/pyside2) | [![Conda Version](https://img.shields.io/conda/vn/freecad/pyside2.svg)](https://anaconda.org/freecad/pyside2) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/pyside2.svg)](https://anaconda.org/freecad/pyside2) |

Installing pyside2
==================

Installing `pyside2` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `pyside2` can be installed with `conda`:

```
conda install pyside2
```

or with `mamba`:

```
mamba install pyside2
```

It is possible to list all of the versions of `pyside2` available on your platform with `conda`:

```
conda search pyside2 --channel freecad
```

or with `mamba`:

```
mamba search pyside2 --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search pyside2 --channel freecad

# List packages depending on `pyside2`:
mamba repoquery whoneeds pyside2 --channel freecad

# List dependencies of `pyside2`:
mamba repoquery depends pyside2 --channel freecad
```




Updating pyside2-feedstock
==========================

If you would like to improve the pyside2 recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/pyside2-feedstock are
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

* [@hmaarrfk](https://github.com/hmaarrfk/)
* [@jan-janssen](https://github.com/jan-janssen/)
* [@jschueller](https://github.com/jschueller/)

