# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Define a function as copy with arguments existing file, new file name.
## Step 2:
Open a function to read.
## Step 3:
Open a function to write
## Step 4:
Copy the contents from existing file to the new file.
## Step 5:
End the program

## PROGRAM:
\*
# Program for copying contents from one file to another
# Developed by: VIGNESH M
# Register number: 212223240176
\*
def copy(fname,new):
with open(fname,"r") as fp1:
with open(new,"w") as fp2:
data1=fp1.read()
fp2.write(data1)
fname=input("Enter an existing file: ")
new=input("Enter name for the file: ")
copy(fname,new)
### OUTPUT:
![image](https://github.com/vigneshvickyu/copy-file/assets/151948835/c8cdfcc6-84dc-43e5-97de-140b1a9e2bcb)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
