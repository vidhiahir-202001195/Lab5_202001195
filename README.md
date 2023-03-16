# IT314 - Software Engineering
# Lab 5 - Static Analysis

## Code which is to be Analysed:

![image](https://user-images.githubusercontent.com/123457236/225583890-634e3e22-5e41-4aef-989f-d5d78e4e59b7.png)

### static Analysis:
- In this code, thjre is a semicolun in line number 20m and 23
- This type of static analysis can help us improve the reliabilty of our code and obmit silly errors.

### Analysis using tool:

#### Use of MYPY tool:

![image](https://user-images.githubusercontent.com/123457236/225584982-0cea4afa-a5f3-4c88-9304-2bf7e9cfdb13.png)

This how the mypy tool will help us detecting the errors when we are unable to finding it manually.

### Types of error which can be detected by mypy tool:
- It helps us to ensure that we are using the variable and functions name correctly.
 For example if we change the variable name at one place and forgot to change it at another place it will detect that error easily.
 
 -One of the disadvantages  of numpy is that it won't affact the dynamic function,
 Hence if any error is made inside the dynamic function,this function won't detect it.
 
 ## Example:
 
 ![image](https://user-images.githubusercontent.com/123457236/225587691-5e6e9192-0c9d-4568-9098-78cb56beb473.png)
 
 ## Running the code using mypy:
 ![image](https://user-images.githubusercontent.com/123457236/225588490-fc9539e5-80ef-48f3-b561-6d7b34895847.png)

 As shown in the code , here the mypy tool won't recognise that the variable names are not the same i.e. new_node and new_var.
 
 
 

