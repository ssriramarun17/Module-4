# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
file=open("story.txt","r") 
count=0 
for lines in file: 
   if lines [0] not in 'T': 
      count+=1 
print(count)
```

## Output
<img width="430" height="81" alt="Screenshot 2025-12-26 213506" src="https://github.com/user-attachments/assets/fe1e5c09-3245-4bb5-874c-e2aa10e68906" />

## Result
Thus the given program has been executed successfully
