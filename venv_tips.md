# Virtual Environments
assume we are inside `path/to/project` <br>
e.g. project is a repo like `FourCoffeePeanuts` <br>
check: https://towardsdatascience.com/virtual-environments-104c62d48c54


## creates an environment called `venv`
* `$ python -m virtualenv venv` <br> 
 

## activates the `venv`
* ### Git Bash 
    `$ source venv/Scripts/activate`
* ### Terminal
    `$ path\to\venv\Scripts\activate.bat` <br>
    in project: `$ venv\Scripts\activate.bat`


## then deactivate <br>
* `$ deactivate`

## delete `venv` (if you want)
* ### Git Bash 
    since it's just a folder, `rm -r venv` will do fine <br>
* ### Terminal
    same logic, but the command is `rd /s venv` <br>


## install the dependencies
* `$ pip install -r requirements.txt` 

## save dependencies
* `(venv) $ pip freeze > requirements.txt`