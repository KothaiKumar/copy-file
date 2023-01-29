# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

Step 2: Using keyword "with" to open the requied file.

Step 3: Again using the with keyword to open the empty file.

Step 4: The empty file is open by using 'W' which is used to write only.

Step 5: The four function is used to take each line from the main file. 

Step 6: The four function is used to take each line from the main file.

Step 7: Print the output.

## PROGRAM:
```python
developed by: Kothai K

registered number: 22006043
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:

    for line in firstfile:
    
             secondfile.write(line)
```  
## OUTPUT:
![copy_file 1](https://user-images.githubusercontent.com/121215739/215323869-d5d8fc3b-c197-47f2-9649-67b2353b3c70.jpg)
![copy_file_2](https://user-images.githubusercontent.com/121215739/215323876-06c0b501-ed16-449d-87f9-2bd6a3fd3c6f.jpg)
![copy_file_3](https://user-images.githubusercontent.com/121215739/215323888-95c235f5-03d7-4590-a8e0-321426cf50ce.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
