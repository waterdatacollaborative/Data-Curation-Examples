
# Data Curation Examples

## Strategy

The proposed method for data curation is based on the [Data Package specification](https://frictionlessdata.io/specs/data-package/).
Data Packages store one or more data resources (e.g. as CSV files), and the metadata associated with them, as specified by a `datapackage.json` file.  

The connection between the data and the metadata is done through a [table schema](https://frictionlessdata.io/specs/table-schema/).
The table schema describes the main features of the data, and can be thought as a machine-readable data dictionary.

To get an idea of how a Data Package-based data repository looks like, see e.g. <https://github.com/datasets/country-codes>.

## Examples

Some examples/tutorials are given as Jupyter notebooks.
The notebooks can be accessed and run interactively thanks to Binder: [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/waterdatacollaborative/data-curation-examples/master)

## Tools

- <https://theodi.org.au/data-curator/>: a GUI application for editing CSV files and table schemas directly
- <https://jsoneditoronline.org/>: Online JSON editor

