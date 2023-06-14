# Read-from-CSV

## AIM:
To write a python program to read the data from cvs file.
## Equipment Required:
PC, Anaconda
## ALGORITHM:
1. Import pandas as pd
2. Read the csv file
3. Print the first 15 and last data using .head() and .tail() method
4. Print the required column and rows
## PROGRAM:
```
import pandas as pd
df = pd.read_csv("/content/student_scores.csv")
print(df.head(15))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Meetha22003992/Read-from-CSV/assets/119401038/31a1d255-38aa-4653-acd7-fd022cbc816e)

![image](https://github.com/Meetha22003992/Read-from-CSV/assets/119401038/db45a74b-ab07-45d2-90d4-2cd9b77d2ae2)

![image](https://github.com/Meetha22003992/Read-from-CSV/assets/119401038/90ff39f0-73f0-4277-974c-83cc2be7ddd3)

![image](https://github.com/Meetha22003992/Read-from-CSV/assets/119401038/32683070-d66f-47bf-b243-4f951c1e3837)

## RESULT:
Thus the program to find the read the cvs file is written and verified using python programming.
