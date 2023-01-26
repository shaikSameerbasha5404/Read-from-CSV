# Read-from-CSV
To write a python program for reading content from a CSV file.
## ALGORITHM:
## Step 1:
Import pandas as pd.
## Step 2:
Read the CSV file using read_csv method.
## Step 3:
Use head and tail method to get the required contents from the file.
## Step 4:
Use len() method to get the number of rows and columns.
## Step 5:
Print the output.
## PROGRAM:
```python
'''
Developed by : Shaik Sameer Basha 
Reference number : 22004926
'''
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT
![6](https://user-images.githubusercontent.com/118707756/214853541-ecb7e04a-eb57-4e42-8454-191a5e02a5d3.jpg)
## RESULT:
Thus a python program is written to read the contents of a CSV file.
