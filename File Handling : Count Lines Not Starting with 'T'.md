# File Handling in Python: merge two files into a third file 

## Aim
To write a Python program that merges the contents of two files into a third file using file handling
operations.

## Algorithm
1. Start the program.
2. Open two input files in read mode.
3. Open a third file in write mode.
4. Read contents of the first file and write into the third file.
5. Read contents of the second file and append into the third file.
6. Close all files.
7. End the program.

## Program
```
def create_file(file_path, content):
with open(file_path, 'w') as file:
file.write(content)
def merge_files(file1_path, file2_path, output_file_path):
f1=open(file1_path,"r")
f2=open(file2_path,"r")
f3=open(output_file_path,"w")
f3.write(f1.read())
f3.write(f2.read())
def read_file(file_path):
with open(file_path, 'r') as file:
return file.read()
```
## Output
<img width="816" height="353" alt="image" src="https://github.com/user-attachments/assets/b340b68d-7d6f-44cd-8bed-a4e35eeba9ce" />

## Result
Thus, the program to merge two files into a third file using File Handling in Python was executed
successfully
