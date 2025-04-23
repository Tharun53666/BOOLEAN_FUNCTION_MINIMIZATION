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
```
Developed by:THARRUN.D
RegisterNumber:212224240170
module BFM(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module BFM1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```
**Truth Table**

![WhatsApp Image 2025-04-22 at 21 52 06_10b96ecd](https://github.com/user-attachments/assets/e38539ad-c95d-4d9b-b71a-8b56d53d6706)
![WhatsApp Image 2025-04-22 at 21 53 16_dc09006e](https://github.com/user-attachments/assets/36c2227c-0bbd-436c-940f-6b648f2023d8)


**RTL**

![WhatsApp Image 2025-04-22 at 21 44 35_ae5fbcc2](https://github.com/user-attachments/assets/e34a7c2e-83a1-4501-8867-6c24a1b5765c)
![WhatsApp Image 2025-04-22 at 21 57 02_2ff2fec5](https://github.com/user-attachments/assets/ebcc4381-909a-452a-9ea5-3527acb75def)


**Timing Diagram**

![WhatsApp Image 2025-04-22 at 21 44 35_66698e6b](https://github.com/user-attachments/assets/c31bf440-fb65-4365-9eca-4384725fda9f)
![WhatsApp Image 2025-04-22 at 21 56 35_a7d916e2](https://github.com/user-attachments/assets/ba6f62af-fdbe-49c7-b1a7-7c032b3f60d6)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

