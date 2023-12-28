# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
get the file name to create user

### Step 2: 
give a new file name to create a copy of a file content

 
### Step 3:
read the file and close the file


### Step 4: 
now the content in the new filr


### Step 5: 
when done print"File Copied Successfully"


### Step 6: 
end the program


## PROGRAM:
```
'''
#Program to copy the file.
#Developed by: sai vivek.R
#RegisterNumber:23003676
'''
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandle=open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```
### OUTPUT:
![Screenshot 2023-12-28 234333](https://github.com/RAGALASAIVIVEK/copy-file/assets/144979718/c8329def-090b-4afc-b32a-21672dec7f60)
![Screenshot 2023-12-28 234402](https://github.com/RAGALASAIVIVEK/copy-file/assets/144979718/ca7f6960-642c-4165-8281-c9eef4411748)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
