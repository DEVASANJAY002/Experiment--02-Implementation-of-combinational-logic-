# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output.
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output. F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D F2=xy’z+x’y’z+w’xy+wx’y+wxy
1.AND gate The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are
high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B
2.OR gate The OR gate is an electronic circuit that gives a high output (1) if one or more of its
inputs are high. A plus (+) is used to show the OR operation. Y= A+B

## Procedure
1.Create a project with required entities.
2.Create a module along with respective file name.
3.Run the respective programs for the given boolean equations.
4.Run the module and get the respective RTL outputs.
5.Create university program(VWF) for getting timing diagram.
6.Give the respective inputs for timing diagram and obtain the results
## Program:
program to implement the given logic function and to verify its operations in quartus using Verilog
programming.
Developed by: DEVASANJAY N
RegisterNumber:  23013004

Code :

F1 : ![Exp2codei](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/5377f445-300e-4575-9f1e-ad35cae3d15c)
F2 : ![Exp2codeii](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/ae80a1bf-1de2-44ec-96fb-5a7672944dbd)

RTL : 
F1 : ![Exp2 f1](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/fb2899a4-573c-4ae7-832b-f4638058d725)
F2 :![Exp2 f2](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/73c73ab1-344d-48a9-a584-f7458595b60c)

Output:
Timing Diagram:
F1 :![Exp2 f1 timing](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/2ed75079-6530-4c4e-a616-2137f196b532)

F2 :![Exp2 f2 timing](https://github.com/DEVASANJAY002/Experiment--02-Implementation-of-combinational-logic-/assets/152069249/624e2e41-e27e-45ac-babb-b4cb967de4a9)

Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
