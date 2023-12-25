# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file.
## ALGORITHM:
### Step 1
Create a spreadsheet with any details in it with extension .csv
### Step 2:
Open google colab and mount the drive for using the created file in the colab
### Step 3:
import pandas package as pdf for reading the csv file using pd.read_csv(filename)
### Step 4:
use the function called head() and tail() for printing the to and bottom of the file and then axes[]used for inding the number of rows and columns
### Step 5:
End of program

## PROGRAM:
  ```
import pandas as pd
f=pd.read_csv('cars (1).csv')
print(f.head(10))
print(f.tail())
print("rows",len(f.axes[0]))
print("columns",len(f.axes[1])
  ```
## OUTPUT:
![image](https://github.com/23006823/Read-from-CSV/assets/138971409/d31248b7-cee7-43de-9be7-a7574de4c35e)

## RESULT:
Thus python program for reading content from a CSV file is successful.
