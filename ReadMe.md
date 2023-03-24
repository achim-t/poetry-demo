## Init
`poetry init`
## Install Virtual Environment
`poetry install`
## Update Something 
For example packages to install

`poetry lock` 
## Info
`poetry env info`

## Update Config to create virtual environments inside the project
`poetry config virtualenvs.in-project true`
## Open Shell
`poetry shell`
## Add packages 
`poetry add requests`

Adds the package (here `requests`) and modifies `pyproject.toml` as well as `poetry.lock`
## Remove packages
`poetry remove requests`

Removes the package (here `requests`) and modifies `pyproject.toml` as well as `poetry.lock`