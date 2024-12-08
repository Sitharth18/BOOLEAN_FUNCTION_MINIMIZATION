
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


![image](https://github.com/user-attachments/assets/0d9267d8-278c-49db-a9d2-7773b72b1066)


![image](https://github.com/user-attachments/assets/3dc3d682-9cc8-4779-a271-a91c9e128cff)



**Output:**



**RTL**


![image](https://github.com/user-attachments/assets/9299554c-9ddd-4749-a58a-c674ac489a4e)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

