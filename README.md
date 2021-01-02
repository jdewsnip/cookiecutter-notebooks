# Cookie-Cutter Notebooks

Template for data science projects using cookie cutter.

## Project creation

```bash
    cookiecutter https://github.com/jdewsnip/cookiecutter-notebooks <project-name>
    cd <project-name>
    conda install --file conda.yaml
```

## Project structure

```bash
│
├── notebooks          <- Jupyter notebooks. 
│
├── references         <- Reference material. 
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│
├── conda.yaml         <- Library dependencies 
│
├── src                <- Source code for use in this project.
│   │
│   ├── R              <- R source code
│   │
│   └── Python         <- Python code
│
└── README.md          <- tox file with settings for running tox; see tox.testrun.org
```

## References

Based on code from https://drivendata.github.io/cookiecutter-data-science and https://github.com/cookiecutter/cookiecutter.
