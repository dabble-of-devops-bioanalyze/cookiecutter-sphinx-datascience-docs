## About

Cookiecutter template + conda env yaml file for data science documentation.

Most of this comes straight from the [Xarray Documentation](https://docs.xarray.dev/en/stable/user-guide/index.html).

It includes extensions for:

* Jupyter Notebooks
* Myst parser
* Sphinx Book Theme

## Quickstart

```bash
cookiecutter https://github.com/dabble-of-devops-bioanalyze/cookiecutter-sphinx-datascience-docs
```


```bash
cd docs-dir
conda env create -f datascience-env.yaml
# alternately, use mamba
# mamba env create -f datascience-env.yaml
make livehtml
```
