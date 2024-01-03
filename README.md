```
Name :- sreenithi.E
Reg no :- 212223220109
```
# Ex:03 Implementation of Half Adder and Full Adder circuit

Implementation of Half Adder and Full Adder circuit

# AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:
Hardware – PCs, Cyclone II , USB flasher Software – Quartus prime

# Theory
Adders are digital circuits that carry out addition of numbers.

# Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

# Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/3ff7fcda-9c59-4e12-9e7f-efdbdc8ffad8)


# Figure -01 HALF ADDER
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/e0adbdd3-d19c-4cff-a4f4-446349a5a419)


# Figure -02 FULL ADDER
Procedure
Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

# Program:
Half Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/d65c7ca6-8df4-4bf4-af40-595e705ebbc3)

# Full Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/21caa654-0347-48e8-8a59-c83d67c12639)


Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming. Developed by:

# Logic symbol
# Half Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/43d99de4-c8cd-46f0-a60e-13c66d0ea620)


# Full Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/bd7e9e0d-7584-44ae-867d-60b04078b397)


# Truthtable
Half Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/bdc11f49-e204-4337-8c25-2dd4287e0690)


# Full Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/c4005607-8291-4d83-9ba9-7fd5ba52f603)

# RTL realization
# Half Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/c3bc8c19-da0a-4203-a505-91f79508557e)

# Full Adder
![image](https://github.com/sreenithi123/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145743046/a4c21c47-929b-47ee-a763-b6a6e185f631)


# Result:
To design a half adder and full adder circuit and verify its truth table in quartus using verilog programming.
