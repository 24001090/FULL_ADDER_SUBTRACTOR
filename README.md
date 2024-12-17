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

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Pooja Priya.B   RegisterNumber:24001090
*/
![Screenshot 2024-12-17 144443](https://github.com/user-attachments/assets/12953d1b-a446-414e-bf89-c05260163bfd)

**RTL Schematic**
![Screenshot 2024-12-17 144454](https://github.com/user-attachments/assets/43aca2f0-d852-4694-8724-270446aa9fc2)
![Screenshot 2024-12-17 144500](https://github.com/user-attachments/assets/5533ad1a-dcf0-4b17-bf24-40bc18521e87)

**Output Timing Waveform**
![Screenshot 2024-12-17 144528](https://github.com/user-attachments/assets/6bc0a5a6-22c2-423c-9e7e-7d91d6b11f55)
![Screenshot 2024-12-17 144537](https://github.com/user-attachments/assets/6f09e0c5-1080-4fc4-a38c-2189aa2e4268)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



