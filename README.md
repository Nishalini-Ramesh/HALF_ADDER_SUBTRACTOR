# NAME: NISHALINI R 
# REG NO: 212224040222

# EXP3 HALF ADDER SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![77f40722-498e-4a6e-a7ba-2f48906870ca](https://github.com/user-attachments/assets/fbe7ca6a-49be-4d68-9a1a-d913e6f6077e)


**Truth Table**

![Screenshot 2025-04-16 091304](https://github.com/user-attachments/assets/82a73513-cf7b-4f86-bea5-7da5d39bc1d8)


![Screenshot 2025-04-16 091320](https://github.com/user-attachments/assets/52bb5934-8944-4c37-b034-d3acd06696b0)

**RTL**

![c029c3f3-1f0b-4626-8288-58ad22add75e](https://github.com/user-attachments/assets/a4490a23-e90d-48a3-a148-64103a3fb824)

**Waveform**

![d2af973b-c869-4df7-96cc-6bf867486834](https://github.com/user-attachments/assets/84d638ee-995d-477c-b509-b8189ec0ef80)

**Result:**
 The Implementation-of-Half-Adder-and-Half Subtractor-circuit is verified successfully.
