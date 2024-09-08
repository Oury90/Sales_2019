# Project Report Sales_2019
![Oury](assets/images/visualization.gif)
# Developing a visualization report by combining Python and Power BI for our electronics store.
## Data Clining using Python 
### installing Dependencies
```Python
   import pandas as pd
import numpy as np
import os
import matplotlib.pyplot as plt
import seaborn as sns
```
### Download dataset
```Python
path='/content/datas'
files = [file for file in os.listdir(path)]
for file in files:
  print(file)
```
output
![Oury](assets/images/data-1.png)
