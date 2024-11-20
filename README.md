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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
module exe02(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
Developed by:Ragasudha R RegisterNumber:24900684*/




**Output:**
![WhatsApp Image 2024-11-20 at 09 01 31_b3b46bc7](https://github.com/user-attachments/assets/26eb20d9-7a3f-4987-8523-f5187d513b87)

**Timing Diagram**
![WhatsApp Image 2024-11-20 at 09 01 32_a5f1a9ba](https://github.com/user-attachments/assets/61e197c2-cd97-4933-af5d-43ab4e1c53e7)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

