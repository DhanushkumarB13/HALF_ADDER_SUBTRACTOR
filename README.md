### NAME: B. DHANUSH KUMAR
### REG NO: 24900615
### EXP 3 - Implementation-of-Half-Adder-and-Half Subtractor-circuit

# HALF_ADDER_SUBTRACTOR


# AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

# Truthtable
![fc204954-6de6-4698-97ad-8d01cef5fac2](https://github.com/user-attachments/assets/24f581d8-81a8-45b1-aab9-792e8ce9605f)

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# Program:
![0ea6a6bd-2b91-460f-9dd3-301a30f1e58d](https://github.com/user-attachments/assets/05ddf031-3389-4a86-8294-24ecf49b8c71)

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

# RTL Schematic
![07d51b1b-d694-412e-9deb-644715937948](https://github.com/user-attachments/assets/5f207073-51e2-41ad-9af6-106dc3397769)

# Output/TIMING Waveform
![a3e916d7-7ce2-4e05-a175-498441ed098f](https://github.com/user-attachments/assets/4f6e67ee-0d4e-4fab-9026-660cb8af3341)

# Result:

Designed a half adder and half subtractor circuit and verified its truth table in Quartus using Verilog programming.
