# Read-from-CSV

## AIM:
To raed from CSV

## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the CSV file using read_csv method
### Step 3:
Use head and tail method to get required contents from the file
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output

## PROGRAM:
```
import pandas as pd
df=pd.read_csv('cars.csv')
print(df.head(3))
print(df.tail(7))
print(df.axes[0],len(df.axes[0]))
print(df.axes[1],len(df.axes[1]))
print(df.loc[2:0,:])
```
## OUTPUT:
![csv](https://github.com/Rohiit2005/Read-from-CSV/assets/138849178/46e77f85-bfbb-4633-a3fe-1dfaef8679fd)


## RESULT:
Thus a python program to read the contents of CSV file has been executed successfully
