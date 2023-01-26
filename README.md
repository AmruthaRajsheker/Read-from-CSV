# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file.

## ALGORITHM:
### Step 1:
Start the python compiler
### Step 2:
Import pandas
### Step 3:
Mention the csv file which is to be read
### Step 4:
Read the contents of the csv file using df.read function.
### Step 5:
End the program

## PROGRAM:
```
program developed by : Amrutha Rajsheker
register number : 22004501

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```

## OUTPUT:
![ouput](/output.png)

## RESULT:
Thus a program to read the contents of csv file using python is executed.
