# My Awesome Python
Just a list of 'awesome' things that'll help in coding Python

## Packages
List of awesome Python packages I've used:

### APIs
* [fastapi](https://fastapi.tiangolo.com/)

### Automation
* [selenium](https://selenium-python.readthedocs.io/index.html)
* [webdriver-manager](https://pypi.org/project/webdriver-manager/)

### CLI
* [typer](https://typer.tiangolo.com/)

### Data Analysis
* [pandas](https://pandas.pydata.org/)

### HTTP
* [requests](https://docs.python-requests.org/en/latest/)

### Parsers
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

### Utilities
#### General
* [pydash](https://pydash.readthedocs.io/en/latest/)

#### Terminal
* [clear](https://pypi.org/project/clear/)
* [pyboxen](https://github.com/savioxavier/pyboxen)

### Validation
* [validators](https://python-validators.github.io/validators/)

## How To's

### String stuff

#### Get random character
It's easy to get a random character with Python's [string](https://docs.python.org/3/library/string.html) module.

Here's a quick example just to show how it can be done:
```python
import string
import random

random.choice(string.ascii_letters + string.digits + string.punctuation)
```

### Terminal stuff

#### Clear the terminal / console with python
Here's a good StackOverflow article about how to clear the console cross-platform style:
* https://stackoverflow.com/questions/517970/how-to-clear-the-interpreter-console

And here's some code how to do it:
```python
import os

def cls():
    os.system('cls' if os.name == 'nt' else 'clear')

cls()
```

And looks like there a package for it already:
* https://pypi.org/project/clear-screen/
