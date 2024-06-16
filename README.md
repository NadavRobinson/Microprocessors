# Microprocessors
PIC16F877 Calculator and Display Project
Authored by Nadav Robinson

==Description==
This project implements a simple calculator using the PIC16F877 microcontroller. The project reads input from a matrix keypad, performs arithmetic operations (addition, subtraction, multiplication, division, power), and displays the results on an LCD screen.

==Features==
Accepts numerical input from a 4x4 matrix keypad-
Supports basic arithmetic operations: addition, subtraction, multiplication, division, and exponentiation-
Displays input and results on a 16x2 LCD-
Indicates errors such as division by zero-
Uses the PIC16F877 microcontroller for processing-

==Hardware Requirements==
PIC16F877 microcontroller
4x4 matrix keypad
16x2 LCD display
Resistors and capacitors for proper operation
Breadboard and connecting wires
Power supply (5V)

==Software Requirements==
MPLAB X IDE
MPLAB XC8 Compiler
PIC programmer (e.g., PICkit 3)

==Project setup==
Circuit Connections
Keypad to PIC16F877:

Connect the rows (R1-R4) and columns (C1-C4) of the keypad to PORTB pins RB0-RB3 and RB4-RB7, respectively.
LCD to PIC16F877:

Connect the data pins (D4-D7) of the LCD to PORTD.
Connect the control pins (RS, RW, E) of the LCD to appropriate pins on PORTE and configure them in the code.
Ensure to connect the VCC, GND, and contrast (V0) pins of the LCD.
Power Supply:

Connect a 5V power supply to the VDD and VSS pins of the PIC16F877.

==Usage==
Programming the PIC:

Use MPLAB X IDE to compile the code and generate the HEX file.
Use a PIC programmer (e.g., PICkit 3) to upload the HEX file to the PIC16F877 microcontroller.
Running the Project:

Power on the circuit.
Use the keypad to input numbers and select operations.
The LCD will display the input and results of the calculations.
If an error occurs (e.g., division by zero), the LCD will display an error message.

==Acknowledgements==
Microchip Technology Inc. for the PIC16F877 microcontroller.
MPLAB X IDE and XC8 compiler for development tools.
