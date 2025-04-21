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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: NAVEEN.S
RegisterNumber: 212223240106

**2a**
~~~
module ex2a(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~a&b&d)|(~b&~d)|(a&b&~c));
endmodule
~~~
**2b**
~~~
module ex2b(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
~~~
**Output**

**2a**

![WhatsApp Image 2025-04-07 at 13 37 37_f6fbd456](https://github.com/user-attachments/assets/afb62b53-039a-4224-a156-5eb6b1e97b16)

**2b**

![WhatsApp Image 2025-04-07 at 13 37 38_a27026d8](https://github.com/user-attachments/assets/c4c0e693-103f-4f3c-a8d9-c1890fe268b0)

**RTL realization**

**2a**

![428376043-7e81e3d0-a02f-4866-9b21-e3848c789032](https://github.com/user-attachments/assets/dc7c5eb9-90c5-48f2-93bb-f6f47d1f1d3d)

**2b**

![428376070-adf7c15e-9709-4f98-ae26-c38704af1e0b](https://github.com/user-attachments/assets/549837b3-336d-4aca-ba44-2d531db537c8)

**RTL**

**2a**

![428376078-ecbdb491-3a4f-4b84-a880-7cc8be923b76](https://github.com/user-attachments/assets/bcf8bc32-2423-4b37-9d47-86e01d398fcb)

**2b**

![428376094-07b65b9a-c07e-4235-a1fc-336b87a9b8d4](https://github.com/user-attachments/assets/e5cf7e3b-0189-4aaf-8b16-1bd6f151e7c1)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

