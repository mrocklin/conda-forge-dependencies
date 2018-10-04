Today I learned that conda-forge maintains a JSON file of all package
dependencies on github.

[github.com/regro/libcfgraph/raw/master/conda-forge.json](https://github.com/regro/libcfgraph/raw/master/conda-forge.json)

This is a small notebook that downloads that json file and turns it into a
Pandas dataframe.  You can run it on Binder here:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/mrocklin/conda-forge-dependencies/master)
