# DIGITAL-LOGIC-BASED-ACCESS-CONTROL-SYSTEM
Digital Logic Password Lock System (Code: 110) using combinational logic gates, switches, and NOT gate simulation in Tinkercad.
This project is a combinational logic circuit designed as a password-based lock system.  
It is built using basic logic gates and binary inputs to simulate how digital systems validate a secure code.

The secret code for this system is **110**.

##  Objective
To design a digital circuit that:
- Takes 3-bit binary input (A, B, C)
- Compares it with predefined password **110**
- Gives output HIGH (LED ON) only when correct code is entered

## Working Principle
- Inputs A, B, C are controlled using switches
- C input is passed through a NOT gate because the required condition is C = 0
- Logic circuit evaluates the combination
- Output LED glows only when input matches **110**

## Logic Used
- A = 1  
- B = 1  
- C = 0 (implemented using NOT gate)
- Final condition = A AND B AND (NOT C)

##  Tools Used
- Tinkercad Circuits
- Digital Logic Gates (AND, NOT)
- Switch inputs
- LED output indicator
