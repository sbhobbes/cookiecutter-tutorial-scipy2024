# Cookiecutter: Project Templates and Much More

## Preparation

* Clone this repository.
* Install Cookiecutter.

## Installation

### pipx (recommended)

```bash
pipx install cookiecutter
```

### pip

```bash
python -m pip install --user cookiecutter
```

### conda

```bash
conda config --add channels conda-forge
conda install cookiecutter
```

See also the installation instructions:

* on the [Cookiecutter GitHub page](https://github.com/cookiecutter/cookiecutter?tab=readme-ov-file#installation)
* in the [Cookiecutter Docs](https://cookiecutter.readthedocs.io/en/latest/installation.html#install-cookiecutter)

### Verify

Check the installed version:

```bash
cookiecutter --version
```

=> 2.6.0

Try it out:

```bash
cookiecutter https://github.com/audreyfeldroy/cookiecutter-pypackage.git
```

## Other Recommended Tools

* `tree`
* [Better Jinja](https://marketplace.visualstudio.com/items?itemName=samuelcolvin.jinjahtml) VSCode extension.
