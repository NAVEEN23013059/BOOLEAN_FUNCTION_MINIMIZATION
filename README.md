# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and
to verify its operations in quartus using Verilog programming. 

Developed by: S.NAVEEN
RegisterNumber: 212223240106

module combinationalcircuit(A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1=(~A)&(~B)&(~C)&(~D);
assign x2=(A)&(~C)&(~D);
assign x3=(~B)&(C)&(~D);
assign x4=(~A)&(B)&(C)&(D);
assign x5=(B)&(~C)&(D);
assign F1=x1|x2|x3|x4|x5;


**RTL realization**
![Screenshot 2024-03-26 002919](https://github.com/NAVEEN23013059/BOOLEAN_FUNCTION_MINIMIZATION/assets/150319555/eabd50da-8503-4c9f-baae-6c1fa6e84c6f)
**Output:**

**Timing Diagram**
![Screenshot 2024-03-26 003020](https://github.com/NAVEEN23013059/BOOLEAN_FUNCTION_MINIMIZATION/assets/150319555/8d3b419a-b542-4e17-b0fb-d47ce635b08e)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

