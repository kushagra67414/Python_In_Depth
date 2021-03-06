# Python_In_Depth

## Day-1

* Numbers and Math Functions
* Common erros

![image](https://user-images.githubusercontent.com/46487696/115961713-3a9ab800-a535-11eb-8197-beff350a03aa.png)
![image](https://user-images.githubusercontent.com/46487696/115961741-5900b380-a535-11eb-87be-8e97d3c4b842.png)

* Indentation Errors
*  Variables & Names
*  String and methods
*  Conditional Statement
*  Functions
*  For and While Loop


## Day-2:


### Functions as Arguments

![image](https://user-images.githubusercontent.com/46487696/116119353-f8f84180-a6db-11eb-8828-b09b49a1a154.png)
![6](https://user-images.githubusercontent.com/46487696/116119491-204f0e80-a6dc-11eb-8c98-e55ca09b97a9.png)



###  List
  * Append
  * insert
  * replace
  * overwrite

![10](https://user-images.githubusercontent.com/46487696/116128621-c273f400-a6e6-11eb-90c1-184e1c3c845e.png)
![9](https://user-images.githubusercontent.com/46487696/116128630-c3a52100-a6e6-11eb-876a-8416ff1c293a.png)
![8](https://user-images.githubusercontent.com/46487696/116128634-c43db780-a6e6-11eb-8054-52b3fff0ce40.png)
![7](https://user-images.githubusercontent.com/46487696/116128638-c4d64e00-a6e6-11eb-8ed4-8d7a90d5660a.png)



### Tuple
  * tuple to changeable list
  * len()
  * and much more

![13 T to L](https://user-images.githubusercontent.com/46487696/116132611-5d6ecd00-a6eb-11eb-9537-3bffb1734c8c.png)
![12](https://user-images.githubusercontent.com/46487696/116132616-5e9ffa00-a6eb-11eb-891a-4a945399818f.png)
![11](https://user-images.githubusercontent.com/46487696/116132619-5f389080-a6eb-11eb-9c35-e0f4775a1251.png)




###  Dictionaries
  * Set()
  * update()
  * pop()
  * get()

![19](https://user-images.githubusercontent.com/46487696/116139415-9dd24900-a6f3-11eb-9479-d720f2539e7a.png)
![18](https://user-images.githubusercontent.com/46487696/116139417-9f037600-a6f3-11eb-8a90-29a100a36e84.png)
![17](https://user-images.githubusercontent.com/46487696/116139421-a034a300-a6f3-11eb-805b-1aed8f3078e9.png)
![16](https://user-images.githubusercontent.com/46487696/116139425-a0cd3980-a6f3-11eb-887b-f98844ff8409.png)
![15](https://user-images.githubusercontent.com/46487696/116139429-a165d000-a6f3-11eb-976e-a0439c50d3d7.png)
![14](https://user-images.githubusercontent.com/46487696/116139433-a1fe6680-a6f3-11eb-9f42-992c68ee2e72.png)



## Day-3:

### List Comprehension

![5](https://user-images.githubusercontent.com/46487696/116193359-d8b49b00-a74c-11eb-9c7f-213d2fbeff7b.png)
![4](https://user-images.githubusercontent.com/46487696/116193364-d9e5c800-a74c-11eb-8dd9-f1d5e457706c.png)
![3](https://user-images.githubusercontent.com/46487696/116193365-da7e5e80-a74c-11eb-801e-a20951a66105.png)
![2](https://user-images.githubusercontent.com/46487696/116193367-da7e5e80-a74c-11eb-9a9c-8e52b6d2660d.png)
![1](https://user-images.githubusercontent.com/46487696/116193369-db16f500-a74c-11eb-8286-00613c055712.png)



### File Handling

A. Reading File

![file2](https://user-images.githubusercontent.com/46487696/116201145-d0f9f400-a756-11eb-9d7b-6d6ccd0cb3b2.png)
![file1](https://user-images.githubusercontent.com/46487696/116201153-d2c3b780-a756-11eb-96c2-5353fd19f80b.png)

B. Reading file using if-else conditional

![Reading through Loop](https://user-images.githubusercontent.com/46487696/116201266-f2f37680-a756-11eb-8ee7-221b8d196ac0.png)
![file 3 1](https://user-images.githubusercontent.com/46487696/116201273-f4bd3a00-a756-11eb-9501-aaeb172b6541.png)

C. Reading Each line of a File 

![readiing line by line](https://user-images.githubusercontent.com/46487696/116201355-0acafa80-a757-11eb-98cb-458955efbc62.png)

D. Writing on a file through console and Reading it

![Opening and Writing](https://user-images.githubusercontent.com/46487696/116201528-351cb800-a757-11eb-8fe4-e3d0f97ea16c.png)
![Opening and Writing 1](https://user-images.githubusercontent.com/46487696/116201520-33eb8b00-a757-11eb-9904-280c8560ca18.png)

E. Creating a file and deleting it through console

![Created new file](https://user-images.githubusercontent.com/46487696/116201622-4f569600-a757-11eb-8a53-4a76fd71baf1.png)
![Removeing created file](https://user-images.githubusercontent.com/46487696/116201614-4e256900-a757-11eb-92dc-ccd8db4ec080.png)

F. Removing Another file using If-else conditional

![Removing using if-else](https://user-images.githubusercontent.com/46487696/116201716-701eeb80-a757-11eb-89da-4249dc4697a6.png)

check-in your working directory, it is removed permanently
![file is deleted](https://user-images.githubusercontent.com/46487696/116201709-6e552800-a757-11eb-92ed-d3e5d4cec5b2.png)



### Debuuging

![debugger 1](https://user-images.githubusercontent.com/46487696/116241519-9a39d300-a782-11eb-9975-ce9f4b55c6c9.png)
![debugger 2](https://user-images.githubusercontent.com/46487696/116241727-db31e780-a782-11eb-9ba1-0fc935a62a13.png)


Code =>

```
import random

def Generatenumber(upper):
    r = random.randint(1,upper)
    return r

def main():
    program = True
    num1 = Generatenumber(10)
    num2 = Generatenumber(10)
    result = num1*num2
    while program:
        ans = input("what is " + str(num1) + " x " + str(num2) + " = ")

        if ans.isdigit():
            if int(ans)==result:
                print("Correct")
                program= False
            else:
                print("Inaccurate")
        else:
            print("Answer must be positive")

x =10
for x in range(x):
    main()
```

### Class and Objects

A. Basic program of class and object

![1](https://user-images.githubusercontent.com/46487696/116252744-7af47300-a78d-11eb-85e5-be01595cf2f2.png)

B.Using "__init__" builtin method

![2](https://user-images.githubusercontent.com/46487696/116252742-7a5bdc80-a78d-11eb-9b3d-f748fa8cb336.png)

C. Using Self in parameters 

![3](https://user-images.githubusercontent.com/46487696/116252741-79c34600-a78d-11eb-94ff-d2208cd27de6.png)

D. overwriting the parameters value

![4](https://user-images.githubusercontent.com/46487696/116252738-79c34600-a78d-11eb-97d5-e38df3f3ba32.png)

E. Deleting an Object

![5](https://user-images.githubusercontent.com/46487696/116252733-77f98280-a78d-11eb-9b35-490c3bc83ea1.png)



## Day-4


### Lambda Function

A. Basic Lambda

![Screenshot (1642)](https://user-images.githubusercontent.com/46487696/116811422-d1372c80-ab66-11eb-9c08-0e106be80d08.png)

B. Function using lambda

![Screenshot (1643)](https://user-images.githubusercontent.com/46487696/116811426-d300f000-ab66-11eb-8037-cc7c7989d671.png)

C. Filter method

![Screenshot (1644)](https://user-images.githubusercontent.com/46487696/116811427-d4321d00-ab66-11eb-9aa2-7697569b12aa.png)

D. Mapping

![Screenshot (1645)](https://user-images.githubusercontent.com/46487696/116811429-d5634a00-ab66-11eb-86d6-f129fc79714f.png)


 ### Read Excel data 
 
 1. First download xlrd package => "pip install xlrd"
 2. Create an excel sheet
 3. Follow the below code and set the path where the excel sheet has been stored
 
 ![Screenshot (1647)](https://user-images.githubusercontent.com/46487696/116813521-bcac6180-ab71-11eb-961c-a917df735b71.png)
![Screenshot (1648)](https://user-images.githubusercontent.com/46487696/116813527-bf0ebb80-ab71-11eb-9568-8ace823d4939.png)

 
**Iterating the sheet row/column**

![Screenshot (1649)](https://user-images.githubusercontent.com/46487696/116813778-24af7780-ab73-11eb-9d20-53f247cbcdeb.png)
![Screenshot (1650)](https://user-images.githubusercontent.com/46487696/116813780-25480e00-ab73-11eb-8a6d-0822855023bf.png)


Source Code =>
```
import xlrd

loc = ("C:\\Users\\Dell\\Desktop\\Python\\ExcelWorksheet.xlsx")

wb = xlrd.open_workbook(loc)

sheet = wb.sheet_by_index(0)

print(sheet.cell_value(0,0))

for i in range(sheet.ncols):
    print(sheet.cell_value((0,i)))
```


### MySql

A. Connecting localhost MySQL

```
import mysql.connector

db = mysql.connector.connect(
    host="localhost",
    user="root",
    password="Kushagra@121"
)
```
![Screenshot (1651)](https://user-images.githubusercontent.com/46487696/116814767-0c8e2700-ab78-11eb-833c-cc0a0d5ed8bc.png)


B. Execution of the table and List checking 

```
import mysql.connector

db = mysql.connector.connect(
    host="localhost",
    user="root",
    password="Kushagra@121",
    database="python"
)

print(db)

a = db.cursor()
# mycursor.execute("CREATE DATABASE  python")
a.execute("SHOW DATABASES")
# mycursor.execute("SELECT * FROM python")


for i in a:
    print(i)
```


### ITERATIONS =>

A. iterating use for loop and next() method

![Screenshot (1652)](https://user-images.githubusercontent.com/46487696/116817241-fcc81000-ab82-11eb-9bf4-544046c79f06.png)


B. iterating using **__iter__()** and **__next__()**

![Screenshot (1653)](https://user-images.githubusercontent.com/46487696/116817245-ffc30080-ab82-11eb-9ea9-88945c7a46e4.png)


### Pickle

Storing data in bytes

![Screenshot (1655)](https://user-images.githubusercontent.com/46487696/116819494-e83d4500-ab8d-11eb-8f3a-ae53a309c909.png)
![Screenshot (1656)](https://user-images.githubusercontent.com/46487696/116819497-ea9f9f00-ab8d-11eb-991f-047679cef486.png)

