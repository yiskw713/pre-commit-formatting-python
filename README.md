# pre-commit-formatting-python

pre-commit hook for formatting python scripts with black, isort and flake8 in docker environment.

## Usage

Setting up pre-commit scripts

```sh
# copy pre-commit hook scripts to the repo where you want to use pre-commit script
$ cp -r .githooks <REPOSITORY>

# set pre-commit script
$ cd <REPOSITORY>
$ git config core.hooksPath .githook
```

