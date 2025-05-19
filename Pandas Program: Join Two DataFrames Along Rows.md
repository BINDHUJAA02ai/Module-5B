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
student_data1 = pd.DataFrame({
 'student_id': ['S1', 'S2', 'S3', 'S4', 'S5'],
 'name': ['Danniella Fenton', 'Ryder Storey', 'Bryce Jensen', 'Ed Bernal', 'Kwame Morin'], 
 'marks': [200, 210, 190, 222, 199]})
student_data2 = pd.DataFrame({
 'student_id': ['S4', 'S5', 'S6', 'S7', 'S8'],
 'name': ['Scarlette Fisher', 'Carla Williamson', 'Dante Morse', 'Kaiser William', 'Madeeha Preston'], 
 'marks': [201, 200, 198, 219, 201]})
print("Original DataFrames:")
print(student_data1)
print("-------------------------------------")
print(student_data2)
print("\nJoin the said two dataframes along rows:")
result_data = pd.concat([student_data1, student_data2])
print(result_data)
```

## Output
![441084815-3600ef6d-183b-4e8d-964c-83984656974e](https://github.com/user-attachments/assets/da96be0f-7f8c-48a4-bf2d-2c4aaab80c98)
![441084870-ec6606d3-3810-434c-9730-6d22493ed409](https://github.com/user-attachments/assets/ff545b6e-5fbd-48c0-aadc-65ce24f7cd4a)

## Result
Thus, the Python program has been successfully created and executed successfully to join the two DataFrames row-wise using pd.concat() and all records from both DataFrames were included in the final output.
