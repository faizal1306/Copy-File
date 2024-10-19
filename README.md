### Date:
# Ex-11:Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End of the program
## PROGRAM:
```
'''Register no:24000006
Developed by: MOHAMED FAIZAL M'''
def copy(text1,newfile):
    with open(text1) as fp:
        with open (newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("text1.txt","file2.txt")
```
### OUTPUT:
![EX 11](https://github.com/user-attachments/assets/7479b9a2-2b12-43ca-8ac8-0a77b90ab8da)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
