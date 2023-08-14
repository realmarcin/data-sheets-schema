# data-sheets-schema

A LinkML schema for Datasheets for Datasets model as published in [Datasheets for Datasets](https://m-cacm.acm.org/magazines/2021/12/256932-datasheets-for-datasets/fulltext)

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [data_sheets_schema](src/data_sheets_schema)
    * [schema](src/data_sheets_schema/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/data_sheets_schema/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>
Use the `make` command to generate project artefacts:

* `make all`: make everything
* `make deploy`: deploys site
</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
