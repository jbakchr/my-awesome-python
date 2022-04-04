# My Awesome Python
Just a list of 'awesome' things that'll help in coding Python

## Packages
List of awesome Python packages I've used:

### Data Analysis
* [pandas](https://pandas.pydata.org/)

### HTTP
* [requests](https://docs.python-requests.org/en/latest/)

## How To's
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
