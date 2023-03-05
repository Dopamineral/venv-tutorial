# Using virtual environments in python
## instructions on how to make

1. make a virtual environment(see below)
2. activate it
3. pip install everything you need
4. in the end export the dependencies to a text file
   


```sh
pip freeze > requirements.txt
```


## Instructions for dummies for the extraction thing



make an environment

```sh
python3.10 -m venv .venv
```

activate environment

```sh
source .venv/bin/activate
```

install dependencies

```sh
pip install -r requirements.txt
```

example script:
```python
import numpy 
print("hello")
```

formatted as shell
```sh
import numpy 
print("hello")
```


