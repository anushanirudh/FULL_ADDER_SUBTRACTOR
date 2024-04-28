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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: R Anirudh

RegisterNumber: 212223230016
*/

**Full Adder**

![Screenshot 2024-04-28 142613](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/7ed1efc2-cd0c-4eec-b26f-33c05a9f5218)


**RTL Schematic**

![Screenshot 2024-04-28 142711](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/8fb4e095-0903-4ed5-9229-172842cf0801)

**Truth Table**

![Screenshot 2024-04-28 142759](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/eeffb2b5-3aea-4f74-b26a-1e26dc5b76a6)


**Output Timing Waveform**

![Screenshot 2024-04-28 142826](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/0345d906-98d5-410d-bfc9-4f95715b341d)

**Full Subtractor**

**Progarm**

![Screenshot 2024-04-28 142943](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/b42dc354-a476-4405-a246-5f92f276e797)

**RTL Schematic**

![Screenshot 2024-04-28 143334](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/4a417992-dcbd-4cdf-a9a9-ce8f639ca794)


**Truth Table**

![Screenshot 2024-04-28 143145](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/c05828e8-5392-4270-a0c1-7de2cf6c3af8)

**Output Timing Waveform**

![Screenshot 2024-04-28 143214](https://github.com/anushanirudh/FULL_ADDER_SUBTRACTOR/assets/151725737/02b95b9e-9c94-49bf-9074-2efe8d6dc1c1)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



