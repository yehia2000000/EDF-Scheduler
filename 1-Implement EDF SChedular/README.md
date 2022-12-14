# Implementation of EDF Schedular  
- implement the thesis instruction in the code  
- Change in Idle Task Function : increment th deadline of idle task which is put in last EDF ready list 
- Change in Increment tick Function : to check the any task finish the delay time and put it in the EDF Ready list and update the deadline of each task  
- create periodic task creation function  : to set the period of the task in TCB to calculate the deadline of each task 

