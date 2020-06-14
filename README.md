# Edge Computing to pre-process livestream videos and be uploaded to IBM Cloud Object Storage (COS)



## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General Info

In this code pattern, we will take in livestream video as input and pre-process the video using OpenCV, Jupyter Notebook and other utility modules for file management. The code will load video into the Jupyter Notebook where we will process every individual frames and is locally stored. 

With the locally stored image, the images are then parsed and processed for detection of movement between frames using frame differencing technique.  



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

