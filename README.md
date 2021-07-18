# Project generator

https://cookiecutter.readthedocs.io/en/latest/index.html

- run cookiecutter

```shell
cookiecutter tools/project_generator/
```

- answer on required questions
```shell
email [ads@nordigy.ru]:
project_name [changeme]: new_awesome_project
project_slug [new_awesome_project]:
version [0.1.0]:
````

- get a default project structure
```shell
  |- Makefile
  |- README.md
  |- new_awesome_project/
  |- pyproject.toml
  |- tests/
```