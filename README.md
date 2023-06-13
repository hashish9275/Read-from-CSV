# Read-from-CSV

## AIM:
To write a python program for copying the contents from one file to another file.

## ALGORITHM:
## Step 1:
Import pandas module as pd.

## Step 2:
Using pd.read_csv() method read the CSV file.

## Step 3:
Using df.head() print the first 10 rows of the CSV file.

## Step 4:
Using df.tail() print the last 5 of the CSV file.

## Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
To write a python program for reading content from a CSV file.
Developed by:  K. R. Hashish Vidya Sagar
Register Number: 212222230047

import pandas as pd
df = pd.read_csv('data1.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
OUTPUT:
1
```
## OUTPUT:
![1](https://github.com/hashish9275/Read-from-CSV/assets/118707521/6f263cfb-95f4-40a5-a3d6-f2d8c7cbab25)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
