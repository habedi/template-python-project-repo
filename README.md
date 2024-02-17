# Template Repository for Python Projects

This repository is as a template for starting Python projects with the following features:

- [Poetry](https://python-poetry.org/) for dependency management
- [pytest](https://docs.pytest.org/en/stable/) for testing
- [Pylint](https://www.pylint.org/) for code linting

It is mainly intended for my personal use to start machine learning data science projects but feel free to use it as a starting point for your own projects.

## Prerequisites

Before you can use this template, make sure you have Python installed on your system. We are going to use [Poetry](https://python-poetry.org/) for dependency management, which needs Python 3.7 or newer.

`pip install poetry`

To initiate the Poetry environment and install the dependency packages, run the following commands in the shell in the root folder of this repository after downloading it.

`poetry update && poetry init`

After that, enter the Poetry environment by invoking the poetry's shell using the following command:

`poetry shell`

Edit the `pyproject.toml` file to update the project name, description, and other metadata.

## License

Files in this repository are licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## CHANGELOG

For a detailed changelog, see the [CHANGELOG.md](CHANGELOG.md) file.