# FoodFormatics
This has been tested on macOs Mojave...

Install homebrew (macOs packages):
- Check to see if you already have this package installed, run `brew info`
- if you do not have brew run:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Install latest pyenv (Python version manager):
- `brew update`
- `brew install pyenv`
- Add this to your ~/.bash_profile `eval "$(pyenv init -)"`

Install pyenv-virtualenv
- `brew install pyenv-virtualenv`
- Add this to your bash_profile `eval "$(pyenv virtualenv-init -)"`

Install python version 3.8 using pyenv and set as default:
- `pyenv install 3.8.0`
- `pyenv global 3.8.0`
- Check python version to ensure this is working properly (`python -V`)

Setting up your environment: 
- Create an environment to install packages. 
- `pyenv virtualenv djangoApp`
- To use this environment use `source activate djangoApp`

Install Django:
- `python -m pip install Django==3.0`
- Run `python -m django --version` to make sure its installed properly
