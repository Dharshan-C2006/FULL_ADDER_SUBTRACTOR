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

Full Adder

![Screenshot 2024-12-03 082131](https://github.com/user-attachments/assets/073b8e52-fbc2-40b3-84ba-4ca34f0c0144)

Full Subtractor

![Screenshot 2024-12-03 082152](https://github.com/user-attachments/assets/fd87d90a-e806-483a-a40e-d005a52e9be5)


**Program:**

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
```
Developed by: C DHARSHAN
RegisterNumber:24900053
```

Full Adder

![Screenshot 2024-11-28 105303](https://github.com/user-attachments/assets/7206cc9d-3e08-4f2c-8e66-c4e8359f4eed)

Full Subtractor

![Screenshot 2024-11-28 105812](https://github.com/user-attachments/assets/0a9a650b-c498-4065-99fc-5b971172451a)


**RTL Schematic**

Full Adder

![Screenshot 2024-11-28 105400](https://github.com/user-attachments/assets/c0e3dcd3-4f60-47c8-ae73-6eb6bb581fcb)

Full Subtractor

![Screenshot 2024-11-28 105831](https://github.com/user-attachments/assets/8b4a1bc7-15eb-49a5-a86c-bf8298d71191)

**Output Timing Waveform**

Full Adder

![Screenshot 2024-11-28 105635](https://github.com/user-attachments/assets/2c409106-8c91-42cb-84b3-9b41419953b3)

Full Subtractor

![Screenshot 2024-11-28 110000](https://github.com/user-attachments/assets/81a3c240-8da0-4e0a-8906-4e15424c3641)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



