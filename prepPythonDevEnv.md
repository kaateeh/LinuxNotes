## Preparation of Python Development Environment

1. `curl -sSL https://install.python-poetry.org | python3 -`
2. add poetry to the PATH: `export PATH="/home/<username>/.local/bin:$PATH"`
3. config poetry to keep all project dependencies in project folders: `poetry config virtualenvs.in-project true`
4. enable autocompletion for bash: `poetry completions bash >> ~/.bash_completion` (I use bash).
5. make a new directory in home directory, let's say *pythonProjects*
6. cd to the *pythonProjects*
7. create new project: `poetry new myAwesomeNewApp`
8. cd to the *myAwesomeNewApp* directory
9. edit *pyproject.toml* to add all the dependencies and such.
10. the rest of fun is in Poetry's docs - they're pretty good.
