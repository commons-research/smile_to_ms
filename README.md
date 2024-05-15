# smile-to-ms

[![Release](https://img.shields.io/github/v/release/pamrein/smile-to-ms)](https://img.shields.io/github/v/release/pamrein/smile-to-ms)
[![Build status](https://img.shields.io/github/actions/workflow/status/pamrein/smile-to-ms/main.yml?branch=main)](https://github.com/pamrein/smile-to-ms/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/pamrein/smile-to-ms/branch/main/graph/badge.svg)](https://codecov.io/gh/pamrein/smile-to-ms)
[![Commit activity](https://img.shields.io/github/commit-activity/m/pamrein/smile-to-ms)](https://img.shields.io/github/commit-activity/m/pamrein/smile-to-ms)
[![License](https://img.shields.io/github/license/pamrein/smile-to-ms)](https://img.shields.io/github/license/pamrein/smile-to-ms)

This is a template repository for Python projects that use Poetry for their dependency management.

- **Github repository**: <https://github.com/pamrein/smile-to-ms/>
- **Documentation** <https://pamrein.github.io/smile-to-ms/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:pamrein/smile-to-ms.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with

```bash
make install
```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version



---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).
