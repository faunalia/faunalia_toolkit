# Faunalia Toolkit - QGIS Plugin

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)

[![pylint](https://github.com/faunalia/faunalia_toolkitlint/pylint.svg)](Nonelint/)


## Generated options

### Plugin

"plugin_name": Faunalia Toolkit
"plugin_name_slug": faunalia_toolkit
"plugin_name_class": FaunaliaToolkit

"plugin_category": Vector
"plugin_description_short": Faunalia Toolkit Plugin
"plugin_description_long": Faunalia Toolkit plugin for spatial analysis
"plugin_description_short": Faunalia Toolkit Plugin
"plugin_icon": default_icon.png

"author_name": Matteo Ghetta
"author_email": info@faunalia.eu

"qgis_version_min": 3.22
"qgis_version_max": 3.99

### Tooling

This project is configured with the following tools:

- [Black](https://black.readthedocs.io/en/stable/) to format the code without any existential question
- [iSort](https://pycqa.github.io/isort/) to sort the Python imports

Code rules are enforced with [pre-commit](https://pre-commit.com/) hooks.  
Static code analisis is based on: PyLint

See also: [contribution guidelines](CONTRIBUTING.md).

## CI/CD

Plugin is linted, tested, packaged and published with GitHub.

If you mean to deploy it to the [official QGIS plugins repository](https://plugins.qgis.org/), remember to set your OSGeo credentials (`OSGEO_USER_NAME` and `OSGEO_USER_PASSWORD`) as environment variables in your CI/CD tool. 


### Documentation

The documentation is generated using Sphinx and is automatically generated through the CI and published on Pages.

- homepage: <None>
- repository: <https://github.com/faunalia/faunalia_toolkit>
- tracker: <None>

----

## License

Distributed under the terms of the [`GPLv3` license](LICENSE).
