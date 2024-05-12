# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Define the function as copy with arguements as existing file name and new file name.

Step 2:
Open the existing file to read.

Step 3:
Open the new file to write.

Step 4:
Copy the contents from existing file to new file.

Step 5:
Get the inputs from the user for existing file and new file. Call the function.

Step 6:
End the program.

## PROGRAM:
```python
/*
A python program for copying the contents from one file to another file:
Developed by: Visalan H
Register no: 212223240183
*/
with open('a.txt','r') as f3:
  msg1=f3.read()
with open('copy.txt','w') as f4:
  f4.write(msg1)
```

### OUTPUT:
### Code
![image](https://github.com/drgbhuvaneswari/Copy-File/assets/152077751/baa552c2-6b4c-49c3-9a61-5fe90a6d632f)
### original file
![image](https://github.com/drgbhuvaneswari/Copy-File/assets/152077751/a9a5f20e-85d5-4b3b-baaa-94527c0d1bf3)
### copied file
![image](https://github.com/drgbhuvaneswari/Copy-File/assets/152077751/8aa96ba5-1b1d-409d-90b3-0f74fa5e1c01)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
