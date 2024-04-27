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

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
```
Developed by: MOENISH BAALAN G
RegisterNumber:212223220057
```

**Full Adder:**

![326155960-b1635526-c14d-4639-9b8c-39d93eeb9516](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/6fe8b239-f9f0-4f80-a748-7af63c9f4314)



**Full Subtractor**
![326155967-e01b6e8a-4d37-43fe-a7d1-938f5945aa37](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/0ff7f257-1339-4f66-a2c6-11b3b74d3d5f)



**RTL Schematic**

**Full Adder:**
![326155979-ded4055d-9f6a-424b-9922-78a85e729181](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/c127eb76-b8a4-43d0-8787-a4fd8b658d93)


**Full Subtractor**
![326155993-9980ec17-7b56-4433-82c8-13e718396d29](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/c07be1af-370b-4fda-8ce8-5cfd9908639f)



**Output Timing Waveform**

**Full Adder:**
![326156035-c95bf5ef-2431-40ba-9994-e043bdb08fe4](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/30bbf192-0624-443b-9593-6bbfe15ab06e)

**Full Subtractor**
![326156043-4c3491f8-2917-4c99-8ce2-3e8232e91014](https://github.com/MoenishBaalan/FULL_ADDER_SUBTRACTOR/assets/147473396/741cbabc-8b28-4e3e-ae8c-1cf3a48c5661)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
