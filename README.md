# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![Screenshot 2024-12-03 085208](https://github.com/user-attachments/assets/de2de283-50db-4cfa-9e89-8fc6de0f5552)


**Procedure**

1 Type the program in Quartus software. 2
 Compile and run the program. 3 Generate the RTL schematic and save the logic
 diagram. 4 Create nodes for inputs and outputs to generate the timing diagram. 5 For
 different input combinations generate the timing diagram
**Program:**

![Screenshot 2024-12-03 085220](https://github.com/user-attachments/assets/42fdc38a-d16f-48af-a090-432a961e661a)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Ashwin kumar RegisterNumber:24900900
*/

**RTL Schematic**

![Screenshot 2024-12-03 085230](https://github.com/user-attachments/assets/d230eb90-8ecf-43b7-890d-56fac967e1fd)



**Output Timing Waveform**

![Screenshot 2024-12-03 085246](https://github.com/user-attachments/assets/6044a5cc-e362-427a-aad4-824f77e5da7a)





**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



