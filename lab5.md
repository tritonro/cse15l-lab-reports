# Lab Report 5
by Rosario Ortiz

## Debugging Scenario

### Post from Student
I am using ssh to edit the buggy files on an ieng6 computer using vim. 

The project directory contains the files GradeServer.java, Server.java , TestListExamples.java, and grade.sh, as well as the directories grading-area,  lib, and student-submission. 

The symptom of the bug is visible in the terminal screenshot below. Rather than accessing the file, this bash script reports "file not found," regardles of whether the file is in the directory or not. I need it to be able to find the file in nested directories as well.  

![Image](images/Screenshot%202023-06-07%20at%206.18.11%20PM.png).  

The screenshot below shows the contents of grade.sh printed to terminal using cat. 
![Image](images/catContents.png)



### Response from TA 

