# FHIR Shorthand cookiecutter
[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a [FHIR Shorthand](https://github.com/FHIR/sushi) project.
* GitHub repo: https://github.com/glichtner/cookiecutter-fhir-shorthand
* Free software: BSD license

## Features
* Creates an empty project structure for FHIR shorthand (SUSHI) projects
* Adds the files created by SUSHI's --init command (version 2.1.1) and some additional files
* Adds two github workflows for validating fsh files and publishing the implementation guide from the master branch
* Adds a [pre-commit](https://pre-commit.com/) config for enforcing file formatting standards 

## Quickstart
- Create project from [cookiecutter](https://github.com/cookiecutter/cookiecutter)
 ```shell
  cookiecutter gh:glichtner/cookiecutter-fhir-shorthand
  ```

- If appropriate environment for [SUSHI](https://github.com/FHIR/sushi) hasn't been setup you can run:
```shell
conda create --name sushi
conda install nodejs
npm install -g fsh-sushi
```

