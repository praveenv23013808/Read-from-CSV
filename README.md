#6.Read-from-CSV

Date: 31.10.2023

## AIM:To write a python program to read contents from a CSV file.
## ALGORITHM:
### Step 1:Import pandas module as pd.
### Step 2:Using pd.read_csv() method read the CSV file.
### Step 3:Using df.head() print the first 10 rows of the CSV file.
### Step 4:Using df.tail() print the last 5 of the CSV file.
### Step 5:Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.
## PROGRAM:
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:', len(f.axes[0]))
print('Col:', len(f.axes[1]))
## OUTPUT:
![280919055-68711323-f5f8-4a65-a33a-2773c6a6bcc4](https://github.com/praveenv23013808/Read-from-CSV/assets/145824728/95c4f93e-81f7-47f7-b4e3-0600dcd3bb12)
## RESULT:
Thus the program executed successfully.
