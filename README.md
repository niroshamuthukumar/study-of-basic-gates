### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**
![DE-a](https://github.com/Bakkiyalakshmiethiraj/study-of-basic-gates/assets/144870983/693182e1-fb67-4908-a67b-a521705a324d)


Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:NIROSHA M
 RegisterNumber: **212223230159**
 
**Logic symbol & Truthtable**
![DE-b](https://github.com/Bakkiyalakshmiethiraj/study-of-basic-gates/assets/144870983/33619043-d1c2-46cd-8b58-2b12beddce08)


**RTL realization Output:** 
![DE-c](https://github.com/Bakkiyalakshmiethiraj/study-of-basic-gates/assets/144870983/8ce14725-071e-465e-a0dc-2e816652d411)


**RTL**
![DE-d](https://github.com/Bakkiyalakshmiethiraj/study-of-basic-gates/assets/144870983/829cd38c-a736-4cb7-b7f2-e40a9aac53b7)


**Result:**
Thus the different digital IC’s are studied and the truth table for different logic gates are verified.


