# Copy file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file. 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output

## PROGRAM:
```Python
with open("trty","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```
### OUTPUT:
#### program file
<img width="649" alt="image" src="https://github.com/Nijeesh-bit/copy-file/assets/89188014/21ab9e46-1fff-4ace-b4e1-c4680576e0b7">

#### Original file(trty.txt)
<img width="960" alt="image" src="https://github.com/Nijeesh-bit/copy-file/assets/89188014/dd6fb748-4a8f-417c-b459-90401d463d6b">

#### Copied file(copy.txt)
<img width="960" alt="image" src="https://github.com/Nijeesh-bit/copy-file/assets/89188014/ce384654-101c-4e8c-85bd-d0f16099bb43">

#### terminal
<img width="901" alt="image" src="https://github.com/Nijeesh-bit/copy-file/assets/89188014/4f6af7c5-18c1-4638-b29d-4eddc12900ef">


## RESULT:
Thus the program is written to copy the contents from one file to another file.
