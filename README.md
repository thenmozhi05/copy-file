# copy-file
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

### Step4:
Write a code to copy the content of the file to a new file.

### Step 5:
Run the program.

### Step 6:
Display the output.

## PROGRAM:
```
Developed By: thenmozhi
Register No: 23005024

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

```

### OUTPUT:

![image](https://github.com/AnnaLahari/copy-file/assets/149365425/77a6cc32-c880-47a2-a0be-3a1c15e05c68)

![image](https://github.com/AnnaLahari/copy-file/assets/149365425/81ab57b4-12b8-4fb1-86c8-d03582d84fd6)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
