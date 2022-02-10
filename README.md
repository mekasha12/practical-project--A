# practical-project--A
import pandas as pd
import pandas as pd 
import numpy as np
import seaborn as sns #visualisation
import matplotlib.pyplot as plt #visualisation
%matplotlib inline 
sns.set(color_codes=True)
# Loading the CSV file into a pandas dataframe.
df = pd.read_csv(“CARS.csv”)
df.head(5)
df = df.drop([‘Model’,’DriveTrain’,’Invoice’, ‘Origin’, ‘Type’], axis=1)
df.head(5)
# For example, here's several helpful packages to load

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)

# Input data files are available in the read-only "../input/" directory
# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
