# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.


## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Connect the supply (+5V) to the circuit Switch ON the main switch If the output is 1, then the led glows.

## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
### Developed by: KESAV DEEPAK SRIDHARAN
### RegisterNumber: 23002011
*/
### HALF SUBTRACTOR
![halfSubtractor Design](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/44930995-eb50-4b9e-a9ac-ee0917134839)

### FULL SUBTRACTOR
![fullSubtractor Design](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/1eb5f4a0-09ba-458a-ad87-dfeda046adb9)
## Truthtable
### HALF SUBTRACTOR
![33e2da4d-5a08-4478-9f37-13f71ae13e6e](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/389b467d-178b-443e-9a87-4088348d981d)

### FULL SUBTRACTOR
![569b5393-1f55-4d44-b41a-a3ad6c6dde02](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/30d936f3-003b-4920-8c7f-d95ad12fe299)

##  RTL realization
### HALF SUBTRACTOR
![halfSubtractor LogicDiagram](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/2d6e8111-7129-429b-8014-5e9ad09fe8c4)
### FULL SUBTRACTOR
![fullSubtractor logic diagram](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/9356808b-7307-4f14-a62e-9d04728f885d)

## Output:
## Timing diagram 
### HALF SUBTRACTOR
![halfSubtractor Waveform](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/2126ca05-157e-4e02-9418-d5db56409488)
### FULL SUBTRACTOR
![fullSubtractor Waveform](https://github.com/KesavDeepak/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/139336019/0f4acdae-c0c0-4ec9-81df-259ad5378439)




## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
