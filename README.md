# EXPERIMENT--01-ALP-FOR-8086
Name : BALAJI K <br>
Roll no : 212221230011 <br>
Date of experiment :





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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AX,78H;
MOV BX,69H;
ADD AX,BX
HLT

ret                     
```


## Output  
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/1cc2a6e8-f1de-4c1f-9c7a-68e5e61d33e7)




## Subtraction   of 8 bit numbers  ALP 
```
MOV AL,68H;
MOV BL,33H;
SUB AL,BL
HLT

ret                     
```
## Output  

![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/eda8a410-84d2-40d3-8d22-90e33e92ebd7)




## Multiplication alp 
```
MOV AL,75H;
MOV BL,12H;
MUL BL
HLT

ret                     

```
 ## Output  
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/1d5e2901-8ee7-48ea-a537-4053b26040b1)





## Division alp 
```
MOV AL,65H;
MOV BL,15H;
DIV BL
HLT

ret                     

```

## Output  

![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/f29fba07-9ff6-4631-ab9d-3177efd10473)


## Programs for logical operations
## AND alp
```
MOV AL,66H;
MOV BL,77H;
AND AL,BL
HLT

ret
```
## Output 
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/08c0dcc1-a7a6-458a-9e65-c4464bc5e4fd)

## OR alp
```
MOV AL,99H;
MOV BL,66H;
OR AL,BL
HLT

ret 
```
## Output
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/b0e1bd14-d7aa-427c-9886-fc76e90b92ad)

## XOR alp
```
MOV AL,85H;
MOV BL,45H;
XOR AL,BL
HLT

ret                                           

```
## Output
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/fe9093c2-c3dc-480a-86d3-4d00b1304cc7)

## NOT alp
```
MOV AL,38H
NOT AL
HLT

ret
```
## Output
![image](https://github.com/balaji-21005757/EXPERIMENT--01-ALP-FOR-8086/assets/94372294/6c81460b-6755-4928-b5a0-0afacea57c16)

## Result :
 Hence ALP on fundamental arithmetic and logical operations is verified and executed.








