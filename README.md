# Read-from-CSV

## AIM:
To write a python program o read data from CSV file.
## ALGORITHM:
### Step 1:
Start the python
### Step 2:
import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.
## PROGRAM:
```
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))

```

## OUTPUT:
![output p](https://user-images.githubusercontent.com/119478098/215330690-d889fb8f-0078-430d-afb5-e8f6fe22e6ae.jpg)


## RESULT:
A python program to read data from CSV files has been created successfully.
