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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
F(A,B,C,D)=AB+CD+AD

module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule


Developed by: RegisterNumber:*/


**RTL realization**

**Output:**

**RTL**

**Timing Diagram**

**Result:**
logic diagram :
<img width="753" height="492" alt="EX 2 BOOLEAN LOGIC DIAGRAM " src="https://github.com/user-attachments/assets/f0b437d5-f8dd-4424-871a-918626c896f7" />

state diagram :
<img width="1313" height="800" alt="EX 2 BOOLEAN FUNCTION " src="https://github.com/user-attachments/assets/38bfd922-e698-425f-be34-44b960cea904" />


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


