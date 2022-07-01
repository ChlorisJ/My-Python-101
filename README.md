# My-Python-101
This is my personal notebook to learn Python :)

## Jupyter notebook 
I use Jupyter to execute my Python statements. It's a handy brower-based graphical interface that has many useful features as a notebook such as to inlcude text, visualization, mathmatical equations and much more. 

## Import pkges
Ughh importing packages... What a piece of work! 

To download:
```
import sys
!{sys.executable} -m pip install pkgname
```

To import:
```
import numpy as np 
import pandas as pd 
import matplotlib.pyplot as plt
```

## Read data
PANDAS comes in to save the day 🐼

- Pandas provides the read_csv() function to read data stored as a csv file into a pandas DataFrame.
- It can also code out an entire dataframe (But let's be honest, who's gonna)
  - To define a dataframe from scratch
```
df = pd.DataFrame(
    {
        "Name": ["Co","Lzx"],
        "Age": [18, 18],
        "Sex": ["female", "female"]
    })
```

## Numpy
Data can come from a wide range of format, collections of information, images and even sound clips. Despite the apparent differences, it might help to think of all types of data as arrays of numbers. The first steps to any analysis is to transform the data into arrays of numbers - the way computers would understand -.


