# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The four function is used to take each line from the main file.

### Step 6:
The four function is used to take each line from the main file.

## PROGRAM:
```
Program to copy file
#Developed by: SABARI S
#Reference no: 22008698
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
### OUTPUT:

![WhatsApp Image 2023-01-26 at 17 03 00](https://user-images.githubusercontent.com/118660461/214828024-c8168481-7988-44f5-97a9-d4c769e1239e.jpg)

![WhatsApp Image 2023-01-26 at 17 03 00](https://user-images.githubusercontent.com/118660461/214828034-9d1f1e88-4041-4575-a3e8-e55776ff07e5.jpg)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
