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
<img width="730" height="896" alt="image" src="https://github.com/user-attachments/assets/bad3bd2b-bb11-42e3-bf64-a456f44f13c5" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: A. KARTHIK
RegisterNumber: 212225220049
module exp2(
input A,B,C,D,
output F
);
assign F=(~A & ~B & ~C & ~D) | 
			( A & ~C & ~D)		  |
			(~B &  C & ~D)      |
			(~A &  B &  C &  D) |
			( B & ~C &  D);
endmodule


**RTL realization**

**Output:**

**RTL**

<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/985d8fb1-edf0-43c7-81ed-70c65be4aa88" />

 Diagram**

<img width="1920" height="1080" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/d5ea5de4-3b0e-4245-b977-f9b5807681a8" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

