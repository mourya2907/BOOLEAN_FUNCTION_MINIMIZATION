# BOOLEAN_FUNCTION_MINIMIZATION

## AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## Equipment Required:

Hardware – PCs, Cyclone II , USB flasher

## Software – Quartus prime

## Theory

## Logic Diagram

## Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program
3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


## Program:

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
### module funct1(a,b,c,d,f1);
### input a,b,c,d;
### output f1;
### assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
### endmodule

### module funct2(w,x,y,z,f2);
### input w,x,y,z;
### output f2;
### assign f2=((~y&z)|(w&y)|(x&y));
### endmodule

Developed by: Mourya G
RegisterNumber: 24006288


## RTL realization

## Output:
![Screenshot 2024-12-08 155139](https://github.com/user-attachments/assets/bf47c1bb-8dc3-41a2-bb5d-0d0de22e0925)

![Screenshot 2024-12-08 155145](https://github.com/user-attachments/assets/0895d179-b3cf-4a71-b111-eaaa9065d214)



## RTL

## Timing Diagram
![Screenshot 2024-12-08 155153](https://github.com/user-attachments/assets/3998eb08-314f-455e-8a1b-9e1b4240dd83)

## Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

