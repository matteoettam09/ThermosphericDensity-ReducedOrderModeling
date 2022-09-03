# ThermosphericDensity-ReducedOrderModeling

<div align="center">

[![Build status](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/workflows/build/badge.svg?branch=master&event=push)](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/actions?query=workflow%3Abuild)
[![Dependencies Status](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/pulls?utf8=%E2%9C%93&q=is%3Apr%20author%3Aapp%2Fdependabot)

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Security: bandit](https://img.shields.io/badge/security-bandit-green.svg)](https://github.com/PyCQA/bandit)
[![Pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/blob/master/.pre-commit-config.yaml)
[![Semantic Versions](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--versions-e10079.svg)](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/releases)
[![License](https://img.shields.io/github/license/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling)](https://github.com/pPoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/blob/master/LICENSE)

Python package for `Thermospheric Density Reduced Order Modeling` created with https://github.com/TezRomacH/python-package-template

</div>

## Description

"POD.py" deals with the POD of density. 

The two other Python codes are some toy examples to prove the methodologies.

## Clone repository with Large Files (LFS)

Please install [git-lfs](https://git-lfs.github.com/) and use this command to clone our repository:

```
git lfs clone https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling.git
```

### Makefile usage

[`Makefile`](https://github.com/PoincareTrajectories/ThermosphericDensity-ReducedOrderModeling/blob/master/Makefile) contains a lot of functions for faster development.

<details>
<summary>1. Download Poetry</summary>
<p>

To download and install Poetry run:

```bash
make poetry-download
```

</p>
</details>

<details>
<summary>2. Install all dependencies and pre-commit hooks</summary>
<p>

Install requirements:

```bash
make install
```

Pre-commit hooks could be installed after `git init` via

```bash
make pre-commit-install
```

</p>
</details>

<details>
<summary>3. Codestyle</summary>
<p>

Automatic formatting uses `pyupgrade`, `isort` and `black`.

```bash
make codestyle

# or use synonym
make formatting
```

Codestyle checks only, without rewriting files:

```bash
make check-codestyle
```

> Note: `check-codestyle` uses `isort`, `black` and `darglint` library

Update all dev libraries to the latest version using one comand

```bash
make update-dev-deps
```

<details>
<summary>4. Cleanup</summary>
<p>
Delete pycache files

```bash
make pycache-remove
```

Remove package build

```bash
make build-remove
```

Delete .DS_STORE files

```bash
make dsstore-remove
```

Remove .mypycache

```bash
make mypycache-remove
```

Or to remove all above run:

```bash
make cleanup
```

</p>
</details>


## Related packages

- [SSMLearn](https://github.com/haller-group/SSMLearn)
- [Codpy](https://github.com/JohnLeM/codpy_alpha)
- [libROM](https://github.com/LLNL/libROM)


## Credits [![🚀 Your next Python package needs a bleeding-edge project structure.](https://img.shields.io/badge/python--package--template-%F0%9F%9A%80-brightgreen)](https://github.com/TezRomacH/python-package-template)

This project was generated with [`python-package-template`](https://github.com/TezRomacH/python-package-template)
