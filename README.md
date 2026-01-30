# EXPERIMENT--01-ALP-FOR-8086
## Name :Abishek P
## Roll no :212224240002
## Date of experiment : 30-01-2026





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
org 100h

mov al,[1100h]

mov bl,[1102h]
add al,bl
mov 1200h,al
hlt

ret
```



## Output  
<img width="991" height="770" alt="image" src="https://github.com/user-attachments/assets/9503b328-fb06-42d6-826c-869613e56a57" />

 
## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov al,[1100h]

mov bl,[1102h]
sub al,bl
mov 1200h,al
hlt

ret
```

## Output  
<img width="980" height="772" alt="image" src="https://github.com/user-attachments/assets/66306736-5970-4639-808b-9cbb350bf4d3" />
## Flag 
<img width="121" height="358" alt="image" src="https://github.com/user-attachments/assets/f1831740-5c37-4434-8941-967f65679aaa" />

## Multiplication alp 
```
org 100h

mov al,[1100h]

mov bl,[1102h]
mul bl
mov 1200h,al
mov 1202h,ah
hlt

ret
```
 ## Output  
<img width="1059" height="772" alt="image" src="https://github.com/user-attachments/assets/cf600472-4469-443b-98ff-f6cda32c4aa1" />


## Division alp 
```
org 100h

mov ax,[1100h]
mov bx,[1102h]
div bx
mov 1200h,ax
mov 1202h,dx
hlt

ret
```
## Output  
<img width="974" height="769" alt="image" src="https://github.com/user-attachments/assets/15b9d57f-af23-44af-bd87-f55c10b8a52c" />

## AND for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
AND al,bl
mov [1200h],al
hlt

ret
```
## Output:
<img width="992" height="776" alt="image" src="https://github.com/user-attachments/assets/7405a995-35c2-4147-8bc9-57b7a9a73e42" />

## OR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
OR al,bl
mov [1200h],al
hlt
```
## Output:
<img width="985" height="784" alt="image" src="https://github.com/user-attachments/assets/2ac07e6e-172c-4be8-a28a-6004679b1b02" />
## NOT for 8 bit alp:
```

org 100h

mov al,[1100h]
NOT al
mov [1200h],al
hlt
```
## Output:
<img width="978" height="775" alt="image" src="https://github.com/user-attachments/assets/1f487864-32b0-4828-8808-94c081ddc68f" />
## NAND for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
AND al,bl
NOT al
mov [1200h],al
hlt
```
## Output:
<img width="978" height="765" alt="image" src="https://github.com/user-attachments/assets/3a5d1235-8e77-4d7f-a73c-a750395d7071" />

## NOR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
OR al,bl
NOT al
mov [1200h],al
hlt
```
## OUtput:
<img width="975" height="772" alt="image" src="https://github.com/user-attachments/assets/a1602eef-c680-4de1-b047-504ab4ee0410" />

## XOR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
XOR al,bl
mov [1200h],al
hlt
```
## output:

<img width="975" height="772" alt="image" src="https://github.com/user-attachments/assets/47bf9e6c-96d0-4479-8978-f9f1f5657712" />

## XNOR for 8 bit alp:
```
org 100h

mov al,[1100h]

mov bl,[1102h]
XOR al,bl
not al
mov [1200h],al
hlt
```

## Output:
<img width="975" height="772" alt="image" src="https://github.com/user-attachments/assets/97efdd67-513d-4abc-8e78-649b494127bf" />

## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








