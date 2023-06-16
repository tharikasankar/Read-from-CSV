# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1: Load the CSV into a DataFrame.
### Step 2: Print the number of contents to be displayed using df.head().
### Step 3: The number of rows returned is defined in Pandas option settings
### Step 4: Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: Increase the maximum number of rows to display the entire DataFrame

## PROGRAM:
```
## Developed by:THARIKA S
## REGISTER NUMBER: 212222230159

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/tharikasankar/Read-from-CSV/assets/119475507/5517c8ef-ee51-4e9e-84df-cbcfd9a920a9)

## RESULT:
