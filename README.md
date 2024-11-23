## EXP3: HALF ADDER AND SUBTRACTOR
# NAME:JASSIR SULTHAN K
# REGISTRATION NO:24901084

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**
![WhatsApp Image 2024-11-22 at 13 45 21_14e408ef](https://github.com/user-attachments/assets/89909e09-f8ae-4b21-a74c-dfa9024c9b89)


Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![WhatsApp Image 2024-11-22 at 13 45 54_e2d21b7b](https://github.com/user-attachments/assets/6dbae48d-b83e-4d46-927d-6f1d5f358807)


Figure -01 HALF ADDER

**Half Subtractor**
![WhatsApp Image 2024-11-22 at 13 42 26_674ab80a](https://github.com/user-attachments/assets/09a6a43c-7d45-43a2-8858-160a2d999fcf)


The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

![WhatsApp Image 2024-11-22 at 13 42 27_35aeb38f](https://github.com/user-attachments/assets/da881bc8-e40e-4bc2-95f7-545b21442348)


Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
![WhatsApp Image 2024-11-22 at 13 45 54_5a40a48a](https://github.com/user-attachments/assets/ef6b8ce4-86cf-4ab2-b29b-ddc1b5608dac)
![WhatsApp Image 2024-11-22 at 13 42 27_a1dd0fcc](https://github.com/user-attachments/assets/ef71755e-4b87-47f5-9b17-1d0173d74807)


