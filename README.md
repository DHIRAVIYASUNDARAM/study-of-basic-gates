# STUDY OF BASIC GATES

# AIM: 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

# EQUIPMENT REQUIRED:

Software – Quartus prime 

# THEORY:

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

# PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM

# DEVELOPED BY: DHIRAVIYA S
# REGISTER NUMBER: 212223040041
 ```
module BASICGATES(a,b,and_out,or_out,not_out,xor_out,xnor_out,nand_out,nor_out);
input a,b;
output and_out,or_out,not_out,xor_out,xnor_out,nand_out,nor_out;
and G1(and_out,a,b);
or G2(or_out,a,b);
not G3(not_out,a);
xor G4(xor_out,a,b);
xnor G5(xnor_out,a,b);
nand G6(nand_out,a,b);
nor G7(nor_out,a,b);
endmodule
 ```
**Truthtable**

![Screenshot 2024-03-27 191551](https://github.com/DHIRAVIYASUNDARAM/study-of-basic-gates/assets/165143880/f169b9e9-52b8-4ab2-b4a5-39e1b1840c4c)

**RTL realization Output:** 

![Screenshot 2024-04-13 113129](https://github.com/DHIRAVIYASUNDARAM/study-of-basic-gates/assets/165143880/c136efa3-202d-46a0-b7cb-fd7ae78f181e)

**RTL**
![Screenshot 2024-04-13 113712](https://github.com/DHIRAVIYASUNDARAM/study-of-basic-gates/assets/165143880/9dfbf968-ffc1-4ae7-b5ed-12a6830bb5c9)


# RESULT:

Thus the different digital IC’s are studied and the truth table for different logic gates are verified.

