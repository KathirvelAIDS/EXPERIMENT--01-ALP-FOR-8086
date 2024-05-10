# EXPERIMENT--01-ALP-FOR-8086
```
Name : KATHIRVEL.A
Roll no :212221230047
Date of experiment ::08.03.2024

```



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







## Programs for arithmetic  operations:




## Addition  of 8 bit ALP 


MOV al,34h

MOV bl,64h

ADD al,bl

hlt



## Output  :




![image](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/59f8646a-9cbe-4f63-a252-7c4b778896d2)



 
## Subtraction   of 8 bit numbers  ALP 

 MOV al,34h

MOV bl,64h

SUB al,bl

hlt



 
## Output :


![image](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/e98e63b1-1504-48f7-ac63-d6e122778847)



## Multiplication alp 


MOV al,34h

MOV bl,64h

MUL bl

hlt



 ## Output  


![image](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/681159dd-38f3-4cb0-b828-bbcb7bbf3fa3)




## Division alp 



MOV al,34h

MOV bl,64h

DIV bl

hlt



## Output  



![image](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/0245ba19-8fc3-4736-a864-291b0e439501)






AND of 8 bit ALP:


MOV AL,33H
MOV BL,44H
AND AL,BL
HLT



![316390657-da0ec872-95ff-4d75-8923-6c8d2f002739](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/5f171357-d976-4a60-b114-5eeb055c60d6)



OR of 8 bit ALP:


MOV AL,45H
MOV BL,66H
OR AL,BL
HLT


![316390609-fa599619-17bc-416a-b662-94c2197c0c42](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/4b223ea7-c39a-4d16-806f-efb68d315421)





NOT of 8 bit ALP:



MOV AL,65H
NOT AL
HLT


![316390577-7ca3fde6-6b68-44c7-a4e6-3fb8e2ec15e9](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/5ed74c12-4cab-4c17-915c-044dc740c17d)




XOR of 8 bit ALP:
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT



![316390559-3c2e879d-70a2-4bbb-bc5f-ce2e1a5d83c4](https://github.com/KathirvelAIDS/EXPERIMENT--01-ALP-FOR-8086/assets/94911373/16222d32-171e-4564-9018-54864488536c)


## Result :



Thus to Write and execute ALP on fundamental arithmetic and logical operations are verified successfully









