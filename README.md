# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 



![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
HALF ADDER
 ![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/4699e57c-1b75-45b5-af9c-2c0a57b01eff)

 FULL ADDER
 ![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/4af47174-ae41-4845-bddc-6d77d93cf17c)



/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:Kavinraj.S
RegisterNumber:23011639
*/
Logic symbol & Truthtable

HALF ADDER

![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/58d6282f-72d1-4d8d-a330-6340d3832b12)

FULL ADDER
![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/3ac0216f-7bc6-4db4-8cae-9a5deceb2d0d)

RTL realization
Half Adder Circuit:
![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/904e8553-4f58-4bd2-97d7-002901622440)


Full Adder Circuit
![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/e51e77b3-820f-45e0-ad70-78be38ff6d17)




### Output:

### RTL
### TIMING DIAGRAM
Half Adder Diagram

![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/50e6d8b7-e18b-4d9f-a9f3-75b4b792de7f)

Full Adder

![image](https://github.com/ROLEX2616/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149988469/e1a61d8e-e433-4ef6-aaef-3876661f76b3)





### TRUTH TABLE 

### Result:
