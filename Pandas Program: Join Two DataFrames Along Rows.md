# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```
import pandas as pd
a=eval(input())
b=eval(input())
print("Original DataFrames:")
c=pd.DataFrame(a)
print(c)
print("-------------------------------------")
d=pd.DataFrame(b)
print(d)
print()
print("Join the said two dataframes along rows:")
e=pd.concat([c,d])
print(e)
```

## Output
![image](https://github.com/user-attachments/assets/6874c045-9a7c-4a66-97c0-92e99e889330)

## Result
Thus,the program has been executed successfully.
