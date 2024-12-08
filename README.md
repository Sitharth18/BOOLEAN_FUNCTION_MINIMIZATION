![image](https://github.com/user-attachments/assets/bc95dee7-c382-4b95-b9b3-6dce1f6d9d15)# BOOLEAN_FUNCTION_MINIMIZATION

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

Developed by:Sitharth.B.S

RegisterNumber: 24900657

```
module experiment2(A,B,C,D,f1,w,x,y,z,f2);
input A,B,C,D,w,x,y,z;
output f1,f2;
assign f1=((~B&~D)|(~A&B&D)|(A&B&~C));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**RTL realization**

![image](https://github.com/user-attachments/assets/97439d18-c0d7-407c-bf0d-a8bc158ee9fb)

**TRUTHTABLE**





**Output:**



**RTL**


![image](https://github.com/user-attachments/assets/17054941-1bd3-407b-922d-06a691557400)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

