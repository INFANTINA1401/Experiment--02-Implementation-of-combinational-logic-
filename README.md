# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

## Software 
Quartus prime
## Theory
 A combinational circuit is a circuit in which the output depends on the present combination of inputs. Combinational circuits are made up of logic gates. The output of each logic gate is determined by its logic function. Combinational circuits can be made using various logic gates, such as AND gates, OR gates, and NOT gates.

## Logic Diagram

![Screenshot 2024-01-02 091824](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/601bcd5f-abd2-4da4-8679-0e143468d2d3)

![Screenshot 2024-01-02 092705](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/1d841768-6398-4f42-bbb3-8498ac2fac76)

## Procedure
Create a New Project:
Open Quartus and create a new project by selecting "File" > "New Project Wizard." Follow the wizard's instructions to set up your project, including specifying the project name, location, and target device (FPGA).

Create a New Design File:
*Once the project is created, right-click on the project name in the Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File," depending on your chosen hardware description language.

Write the Combinational Logic Code:
*Open the newly created Verilog or VHDL file and write the code for your combinational logic.

4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will analyze your code, synthesize it into a netlist, and perform optimizations based on your target FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process, Quartus will display them in the Messages window.

*Review and fix any issues in your code if necessary. *View the RTL diagram.

6.Verification:

*Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click on Node Finder > Click On "List" > Select All.

*Give the Input Combinations according to the Truth Table and then simulate the Output Waveform.
## Program:
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by:INFANTINA MARIA L 
RegisterNumber:23012526  

## RTL realization

## Output:
![CODE IMPLEMENTATION](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/4b8a9bda-055c-49ba-a7b9-399bb2742f50)
![WAVEFORM IMPLEMENTATION](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/c04ffff1-23da-4249-8898-ddc6a74cb3dd)

## RTL
![LOGIC GATE IMPLEMENTATION](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/6738f1de-353c-4de2-a2ae-7ce092389d4a)

## Timing Diagram
![TIMELINE IMPLEMENTATION](https://github.com/INFANTINA1401/Experiment--02-Implementation-of-combinational-logic-/assets/147313821/b2646966-d9c1-419c-bf86-a6bd714716ef)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
