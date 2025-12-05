About r-gdalraster-feedstock
============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-gdalraster-feedstock/blob/main/LICENSE.txt)


About r-gdalraster
------------------

Home: https://github.com/USDAForestService/gdalraster

Package license: MIT

Summary: API bindings to the Geospatial Data Abstraction Library ('GDAL', <https://gdal.org>). Implements the 'GDAL' Raster and Vector Data Models. Bindings are implemented with 'Rcpp' modules. Exposed C++ classes and stand-alone functions wrap much of the 'GDAL' API and provide additional functionality. Calling signatures resemble the native C, C++ and Python APIs provided by the 'GDAL' project. Class 'GDALRaster' encapsulates a 'GDALDataset' and its raster band objects. Class 'GDALVector' encapsulates an 'OGRLayer' and the 'GDALDataset' that contains it. Initial bindings are provided to the unified 'gdal' command line interface added in 'GDAL' 3.11. C++ stand-alone functions provide bindings to most 'GDAL' "traditional" raster and vector utilities, including 'OGR' facilities for vector geoprocessing, several algorithms, as well as the Geometry API ('GEOS' via 'GDAL' headers), the Spatial Reference Systems API, and methods for coordinate transformation. Bindings to the Virtual Systems Interface ('VSI') API implement standard file system operations abstracted for URLs, cloud storage services, 'Zip'/'GZip'/'7z'/'RAR', in-memory files, as well as regular local file systems. This provides a single interface for operating on file system objects that works the same for any storage backend. A custom raster calculator evaluates a user-defined R expression on a layer or stack of layers, with pixel x/y available as variables in the expression. Raster 'combine()' identifies and counts unique pixel combinations across multiple input layers, with optional raster output of the pixel-level combination IDs. Basic plotting capability is provided for raster and vector display. 'gdalraster' leans toward minimalism and the use of simple, lightweight objects for holding raw data. Currently, only minimal S3 class interfaces have been implemented for selected R objects that contain spatial data. 'gdalraster' may be useful in applications that need scalable, low-level I/O, or prefer a direct 'GDAL' API.

Development: https://github.com/USDAForestService/gdalraster

Documentation: https://usdaforestservice.github.io/gdalraster/

About r-gdalraster
------------------

Home: https://github.com/USDAForestService/gdalraster

Package license: MIT

Summary: API bindings to the Geospatial Data Abstraction Library ('GDAL', <https://gdal.org>). Implements the 'GDAL' Raster and Vector Data Models. Bindings are implemented with 'Rcpp' modules. Exposed C++ classes and stand-alone functions wrap much of the 'GDAL' API and provide additional functionality. Calling signatures resemble the native C, C++ and Python APIs provided by the 'GDAL' project. Class 'GDALRaster' encapsulates a 'GDALDataset' and its raster band objects. Class 'GDALVector' encapsulates an 'OGRLayer' and the 'GDALDataset' that contains it. Initial bindings are provided to the unified 'gdal' command line interface added in 'GDAL' 3.11. C++ stand-alone functions provide bindings to most 'GDAL' "traditional" raster and vector utilities, including 'OGR' facilities for vector geoprocessing, several algorithms, as well as the Geometry API ('GEOS' via 'GDAL' headers), the Spatial Reference Systems API, and methods for coordinate transformation. Bindings to the Virtual Systems Interface ('VSI') API implement standard file system operations abstracted for URLs, cloud storage services, 'Zip'/'GZip'/'7z'/'RAR', in-memory files, as well as regular local file systems. This provides a single interface for operating on file system objects that works the same for any storage backend. A custom raster calculator evaluates a user-defined R expression on a layer or stack of layers, with pixel x/y available as variables in the expression. Raster 'combine()' identifies and counts unique pixel combinations across multiple input layers, with optional raster output of the pixel-level combination IDs. Basic plotting capability is provided for raster and vector display. 'gdalraster' leans toward minimalism and the use of simple, lightweight objects for holding raw data. Currently, only minimal S3 class interfaces have been implemented for selected R objects that contain spatial data. 'gdalraster' may be useful in applications that need scalable, low-level I/O, or prefer a direct 'GDAL' API.

Development: https://github.com/USDAForestService/gdalraster

Documentation: https://usdaforestservice.github.io/gdalraster/

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_aarch64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_ppc64le_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=osx&configuration=osx%20osx_arm64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=26280&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-gdalraster-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.5" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--gdalraster-green.svg)](https://anaconda.org/conda-forge/r-gdalraster) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-gdalraster.svg)](https://anaconda.org/conda-forge/r-gdalraster) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-gdalraster.svg)](https://anaconda.org/conda-forge/r-gdalraster) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-gdalraster.svg)](https://anaconda.org/conda-forge/r-gdalraster) |

Installing r-gdalraster
=======================

Installing `r-gdalraster` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-gdalraster` can be installed with `conda`:

```
conda install r-gdalraster
```

or with `mamba`:

```
mamba install r-gdalraster
```

It is possible to list all of the versions of `r-gdalraster` available on your platform with `conda`:

```
conda search r-gdalraster --channel conda-forge
```

or with `mamba`:

```
mamba search r-gdalraster --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-gdalraster --channel conda-forge

# List packages depending on `r-gdalraster`:
mamba repoquery whoneeds r-gdalraster --channel conda-forge

# List dependencies of `r-gdalraster`:
mamba repoquery depends r-gdalraster --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-gdalraster-feedstock
===============================

If you would like to improve the r-gdalraster recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-gdalraster-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)
* [@ctoney](https://github.com/ctoney/)

