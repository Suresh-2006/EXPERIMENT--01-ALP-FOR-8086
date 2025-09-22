# EXPERIMENT 01 ALP FOR 8086
### Name : Suresh S
### Roll no : 212223040215






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

## Addition  of 16 bit ALP (Register Mode)
```
mov ax,5d89h
mov bx,2521h 

add ax,bx
ret       
```



## Output  

<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/00952bba-1acf-4fe6-bd90-13be75a89e17" />


## Subtraction  of 16 bit numbers  ALP (Immediate Mode) 
```    
mov ax,5d89h

sub ax,2521h
ret      
```
## Output
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/94f80f9a-8b47-45d8-995e-ae752fa36a1f" />


## Multiplication alp  (Direct Memory Mode)
```
NUM DW 2521h

MOV AX, 5D89h

MUL NUM       
ret       
```
 ## Output  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5532dd7f-25dc-463d-b3e6-220727cdc435" />




## Division alp (Register Indirect Mode)
```
mov ax,5d89h
mov bx,[2521h]
div bx
ret

```
## Output  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e62b8b97-4ddc-46a4-b42c-286ecf76b9bd" />



## AND  of 16 bit ALP (Register Mode)
```
mov ax,5d89h
mov bx,2521h  

AND ax,bx
ret       
```



## Output  
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/ee606f9d-56a0-42d8-bf7b-7491e3d7addc" />


## OR  of 16 bit ALP (Register Mode)
```
 mov ax,5d89h
 mov bx,2521h 
 
 OR ax,bx
 ret       
```



## Output  

<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/df71e324-7fd7-4d73-9c54-7acc26a9bfc8" />


## NOT  of 16 bit ALP (Register Mode)
```
mov ax,5d89h

NOT ax
ret      
```



## Output  
<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/3e141d6c-dd99-43c1-bb41-e2dec4a6694a" />



## XOR  of 16 bit ALP (Register Mode)
```
mov ax,5d89h
mov bx,2521h 

XOR ax,bx
ret     
```



## Output  
<img width="1920" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/5ec2f58a-9216-4130-bd05-3871eff36729" />


## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








