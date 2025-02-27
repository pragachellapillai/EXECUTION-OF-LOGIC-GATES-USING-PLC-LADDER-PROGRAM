# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Pragaharshitha NC
 # REGISTER NUMBER :212222110033
 # DEPARTMENT :CSE(IOT)
 # YEAR : 3rd year

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:


Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
 AND GATE:

![image](https://github.com/user-attachments/assets/74a55a9e-5db8-4e75-888a-08c5d00b1af6)

OR GATE:

![360785381-f0fd4784-ae28-4161-ab73-d1097ffc4be6](https://github.com/user-attachments/assets/ce372065-36eb-459e-8342-71937deb84ef)


NOT GATE:

![360786123-8b29c5e5-2507-49fa-be88-c92e4f43779d](https://github.com/user-attachments/assets/84dd5a8c-c236-4007-ae68-b6ba8a47e8e8)

NAND GATE:

![360786272-037f1140-ef47-4f02-97f9-e1b560122009](https://github.com/user-attachments/assets/e0535055-1bee-4b64-b0bc-d4beb013cfbf)

NOR GATE:

![360786379-b7287452-bd63-42cf-8c1d-bda5479be303](https://github.com/user-attachments/assets/738f8ba0-98b0-4e59-a668-188021536d34)

EX-OR GATE:

![360787920-520d92d4-cd35-4870-87b4-4a60bd552a28](https://github.com/user-attachments/assets/6ba8986d-e27f-47e6-ad50-2d9a6b2a5012)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
AND GATE:

![360761370-b9554b06-a7eb-4948-99c5-4ba076008c1d](https://github.com/user-attachments/assets/472fb675-3c31-491d-8b28-bbcc939da62c)

OR GATE:

![360779768-baaf1dae-6bc8-46be-b49e-05b1f1093021](https://github.com/user-attachments/assets/fbabf91e-73fe-4b75-87ec-f78b0835434e)

NOT GATE:
![360775053-4a1ce93d-cc6b-45c6-a550-10b07fe1d7f8](https://github.com/user-attachments/assets/266bad0e-7a5f-42c2-b014-0034d3c4f946)

NAND GATE:

![360761087-e0717d43-bee3-4211-8372-11cbd742476a](https://github.com/user-attachments/assets/497e4f5f-f8ac-47a8-b748-7d127ef3f60d)

NOR GATE:

![360771865-9022c8fc-0a86-447f-9669-42ba8a48d9ba](https://github.com/user-attachments/assets/98aec9e3-8a4f-46a7-a9e5-5d5f1cf6acb3)

EX-OR GATE:

![360788342-235aad23-25d5-4362-9f30-4d70d8a1077f](https://github.com/user-attachments/assets/82931ad6-5c66-4e29-b262-4031eca194c4)


# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
