# <pre>             IT 314 - Software Engineering </pre> 
### Lab 5 : Static Analysis
### Student Name : Kunal Hotwani
### Student ID: 202001468
##
### Selected tool : Pylint
### Selected Repo : <a href = "https://github.com/silshack/flaskr"> flaskr </a>
##

#### 1) <a href = "https://github.com/silshack/flaskr/blob/master/flaskr.py"> flaskr.py </a>
    Tool Output : 
![image](https://user-images.githubusercontent.com/124347789/227485340-4e6ccdec-99cf-41ac-9049-3b206a519ee3.png)

#### 2) <a href = "https://github.com/silshack/flaskr/blob/master/flaskr_tests.py"> flaskr_tests.py </a>
    Tool Output : 
![image](https://user-images.githubusercontent.com/124347789/227486191-c774c299-81a1-4b24-9136-4790c9df10dd.png)

#### Understanding of errors:

  

flaskr.py


1.  E0401: Unable to import 'Task' - this could be due to a missing module or package
    
2.  C0103: Variable name "rv" doesn't conform to snake_case naming style
    
3.  C0103: Variable name "ab" doesn't conform to snake_case naming style
    
4.  C0103: Variable name "f" doesn't conform to snake_case naming style
    
5.  W0613: Unused argument 'error'
    
6.  C0116: Missing function or method docstring
    
7.  C0116: Missing function or method docstring
    
8.  C0116: Missing function or method docstring
    
9.  R1735: Consider using dict literals instead of a call to dict.
    

  
  

flaskr_tests.py

  

1.  C0116: Missing function or method docstring
    
2.  C0103: Variable name "r" doesn't conform to snake_case naming style
    
3.  C0103: Variable name "y" doesn't conform to snake_case naming style
    
4.  C0103: Variable name "ru" doesn't conform to snake_case naming style
    
5.  C0103: Variable name "y" doesn't conform to snake_case naming style
    
6.  C0103: Variable name "ry" doesn't conform to snake_case naming style
    
7.  C0103: Variable name "ry" doesn't conform to snake_case naming style
    
8.  R1735: Consider using dict literals instead of a call to dict.
