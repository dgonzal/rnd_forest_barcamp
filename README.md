# sportalliance_rnd_forest_barcamp

Repository with all needed to run the barcamp.

##What are we going to do during the workshop?

- install python 
- install jupyter notebook
- install libraries & import them
  - pandas & scikit learn
- download data from kaggle
- introduction to pandas 
- first look at data from kaggle 
- train a decision tree 
- train a random forest 
- last word on performance

This repository will consist of a jupyternootebook file which contains the documentation of what
we will be looking at and all python code needed. 


## Installation of python & jupyter

The installation can be either done through homebrew or through anaconda and data from kaggle will be used. 
Since anaconda is a GUI Tool no further documentation will be given. For homebrew the following commands need to be run 
in a terminal

- Install homebrew on your machine
```console
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Update brew 
```console
$ brew update && brew doctor
```

- Install python 
```console
$ brew install python
```

- Install jupyter
```console 
$ brew install jupyter
```

from here on everything else will be done in the jupyter notebook.

## Disclaimer

The above mentioned method is not recommended for active use in work enviroments. 
Please use additional libraries like __pyenv__, __pipenv__ or __pip__. 
With these virtual enviroments can be created and used for different projects. The usage of a virtual enviroment per project 
is __very__ pythonic and helps prevent usual problems like library incompatibilities.     

