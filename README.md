## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

# General Info

This project is 

# Foobar

Foobar is a Python library for dealing with word pluralization.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the dependencies.


```bash


pip install ibm-cos-sdk==2.0.1 #IBM SDK for Python
pip install os-win 
pip install opencv-python
pip install pytest-shutil
pip install glob2
pip install numpy


```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
