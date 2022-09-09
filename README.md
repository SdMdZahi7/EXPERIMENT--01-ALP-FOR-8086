# EXPERIMENT--01-ALP-FOR-8086
~~~
Name : SYED MUHAMMED ZAHI
Roll no : 212221230114
Date of experiment : 9/9/2022
~~~
## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







### Programs for arithmetic  operations
## Addition  of 8 bit ALP 
## Program
~~~
name "ADDITION"
org 200h
MOV AX,05H;
MOV BX,02H;
ADD AX,BX;
MOV CX,AX;
MOV AX,00H;
HLT;
~~~
## Output  
## Loading AX and BX register with the Numbers whose Addition has to be found :
![image](https://user-images.githubusercontent.com/94187572/189361984-d1e8059f-b60b-46f6-b362-18079452927c.png)
![image](https://user-images.githubusercontent.com/94187572/189362018-bd414dab-e0b2-442f-b26e-b70bd065a852.png)
![image](https://user-images.githubusercontent.com/94187572/189362066-35c85772-0686-45f3-ba19-973822d025b2.png)
## Performing 8-bit Addition using "AND" instructions :
![image](https://user-images.githubusercontent.com/94187572/189362159-fa2b49d8-51f2-4fdb-af53-12510be0f195.png)
## Moving the data to CX register :
![image](https://user-images.githubusercontent.com/94187572/189362265-baf96542-4d3a-4072-9595-da5b1ede5e75.png)
## Resetting the AX register :
![image](https://user-images.githubusercontent.com/94187572/189362327-a8091f7e-4a07-4bf8-a189-5bbf4d283c91.png)
## End of the execution :
![image](https://user-images.githubusercontent.com/94187572/189362390-b27cbcd0-faef-405c-875e-d8b3dc722395.png)
## Status of various flags :
![image](https://user-images.githubusercontent.com/94187572/189362695-9475e391-e6fc-4951-b163-a36b9efc980f.png)


## Subtraction   of 8 bit numbers  ALP 
## Program
~~~
name "SUBTRACTION"
org 200h
MOV AX,06H;
MOV BX,04H;
SUB AX,BX;
MOV CX,AX;
MOV AH,00H;
HLT;
~~~
## Output  
## Loading AX and BX register with the Numbers whose Subtraction has to be found :
![image](https://user-images.githubusercontent.com/94187572/189362911-241dcfbc-21fb-4bfa-9179-1d6bfd7f7e9a.png)
![image](https://user-images.githubusercontent.com/94187572/189362935-6a8bd744-640e-41c8-a338-165b7ed31b17.png)
![image](https://user-images.githubusercontent.com/94187572/189362962-654b5010-8cef-43a1-bf6a-ba7403787b64.png)
## Performing 8-bit Subtraction using "SUB" instructions :
![image](https://user-images.githubusercontent.com/94187572/189363038-e68d8a02-735c-4610-8cbf-270ac47c45fc.png)
## Moving the data to CX register :
![image](https://user-images.githubusercontent.com/94187572/189363130-6b076db8-59f0-4696-9c63-34e9c48f7257.png)
## Resetting the AX register :
![image](https://user-images.githubusercontent.com/94187572/189363231-12afc691-2862-4bb6-b3f9-83e32c2537cc.png)
## End of the execution :
![image](https://user-images.githubusercontent.com/94187572/189363298-13f15b20-8c2d-4536-a90f-281ed9e7c7f1.png)
## Status of various flags :
![image](https://user-images.githubusercontent.com/94187572/189363341-1159acdc-0733-460f-ad79-98a8730b1ecd.png)



## Multiplication alp 
## Program
~~~
name "MULTIPLICATION"
org 200h
MOV AL,02H;
MOV BL,03H;
MUL BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
## Output  
## Loading AL and BL register with the Numbers whose Multiplication has to be found :
![image](https://user-images.githubusercontent.com/94187572/189363634-666f4c60-17b6-4212-b50e-6fed5f0ff62a.png)
![image](https://user-images.githubusercontent.com/94187572/189363689-a99e4969-d1fe-4e61-8f89-3ce82cd1bfdc.png)
![image](https://user-images.githubusercontent.com/94187572/189363755-b4100900-c5b6-45ee-b3fa-5aff039f33fd.png)
## Performing 8-bit Multiplication using "MUL" instructions :
![image](https://user-images.githubusercontent.com/94187572/189364022-25429815-0363-47d5-acc4-6b68ff0f1532.png)
## Moving the data to CL register :
![image](https://user-images.githubusercontent.com/94187572/189364093-ca49886a-ac5e-41bf-b9c7-a2de41c6820d.png)
## Resetting the AL register :
![image](https://user-images.githubusercontent.com/94187572/189364291-9d4dd4f0-7ac3-40b0-9a81-43a97290cae2.png)
## End of the execution :
![image](https://user-images.githubusercontent.com/94187572/189364382-8b3e11ff-7fc8-47d4-ad0e-4d0361a77c71.png)
## Status of various flags :
![image](https://user-images.githubusercontent.com/94187572/189364463-618f9736-c7ae-4a7e-932d-79e12140db91.png)



## Division alp 
## Program
~~~
name "DIVISION"
org 100h
MOV AL,20H;
MOV BL,10H;
DIV BL;
MOV CL,AL;
MOV AL,00H;
HLT;
~~~
## Output  
## Loading AL and BL register with the Numbers whose Division has to be found :
![image](https://user-images.githubusercontent.com/94187572/189364780-e4132b9e-ba73-4366-9441-db67f0a0cf38.png)
![image](https://user-images.githubusercontent.com/94187572/189364810-3b6cc6f4-9609-44eb-a0f0-fec50a143e4e.png)
![image](https://user-images.githubusercontent.com/94187572/189364826-1467651e-dcf9-4da2-a8b7-8ad40a5d5db8.png)
## Performing 8-bit Division using "DIV" instructions :
![image](https://user-images.githubusercontent.com/94187572/189364880-19d41317-d791-448f-8452-da631edc8939.png)
## Moving the data to CL register :
![image](https://user-images.githubusercontent.com/94187572/189364968-02dfe241-8812-43b2-9df5-d2189bd25975.png)
## Resetting the AL register :
![image](https://user-images.githubusercontent.com/94187572/189365032-47bf8e9f-8492-4985-8182-bc0b284a0974.png)
## End of the execution :
![image](https://user-images.githubusercontent.com/94187572/189365101-5bd43d5f-417e-44a3-bdef-e24e59ee11b2.png)
## Status of various flags :
![image](https://user-images.githubusercontent.com/94187572/189365258-09c4692a-3ac4-4769-b1d6-c753eb0262b7.png)
## Result :
ALP on fundamental arithmetic and logical operations for 8086 is written and executed.


 








