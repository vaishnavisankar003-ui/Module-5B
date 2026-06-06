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

student_data1 = {
    'Name': ['Alex', 'John'],
    'Marks': [85, 90]
}

student_data2 = {
    'Name': ['David', 'Sara'],
    'Marks': [78, 92]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

new_df = pd.concat([df1, df2], axis=0)

print(new_df)
```

## Output
<img width="402" height="132" alt="image" src="https://github.com/user-attachments/assets/9af48ff7-c8cb-4e2e-aed1-e9bad05cc3eb" />

## Result
Thus, the Python program using Pandas to join two DataFrames through row-wise concatenation and assign the data to a new DataFrame was executed successfully and the output was verified.
