# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
```
import pandas as pd
df = pd.read_csv("C:/Users/sst/Downloads/bba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="673" alt="292438765-0cedb2c3-520b-4ba6-9478-97986bbf49c5" src="https://github.com/Naveen1825/Read-from-CSV/assets/138969868/29f3c2e3-2743-4d61-bf29-9b8cc9f0bb1f"><br>
<img width="960" alt="292439460-e7837c6c-10a3-4ee3-a890-b30f6f2ab089" src="https://github.com/Naveen1825/Read-from-CSV/assets/138969868/9fd0e665-272b-49c3-840a-4e819ee66322">

## RESULT:
Thus python program for reading content from a CSV file is successful.
