# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:Import pandas as pd
### Step 2: Read the csv file
### Step 3: Print the first 15 and last data using .head() and .tail() method
### Step 4: Print the required column and rows


## PROGRAM:
``
import pandas as pd
df = pd.read_csv("/content/student_scores.csv")
print(df.head(15))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/Meetha22003992/Read-from-CSV/assets/119401038/cf4f4109-f49c-47e6-828d-f9904b279651)

## RESULT:
