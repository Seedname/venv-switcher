# Installation
Add the following line to .zshrc file:
`source ~/location/to/venv-switcher/venv`
# Usage
`venv -n/--new VENV_NAME`: Create new virtual environment in ~/.venv and switch to it  
`venv -l/--list`: List virtual environments  
`venv -rm/--remove VENV_NAME`: Remove virtual environment & deactivate if currently in environment.  
`venv VENV_NAME`: Switch to virtual environment. Deactivate if currently in environment.  
