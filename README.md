# Digital-Stock-Inventory-Management-System
Overview
This project is a personal endeavor created as part of a Computer Network assignment to design a digital stock inventory system for ACME Toy Company. It features a circuit designed in Logisim 2.7.1 that manages stock changes across different months of the year using only basic logic gates and subcircuits. The project emphasizes secure inventory management using hardware logic to minimize cybersecurity risks.

# Features

1)Month Decoder and Logic:

Decodes the month input (0-15) into five categories: January, Even Months, Odd Months, December, and Error.

Built with a 4-to-16 decoder and a custom month logic subcircuit.

2)Stock Management System:

Adjusts stock levels (0-15 pallets) using a 4-bit adder/subtractor based on month-specific rules.

Handles positive and negative changes with a d-latch for stock memory and error detection for invalid inputs.

3)Error Handling:

LED display alerts users in case of month errors or invalid inputs.

# Circuit Design

Part A: Month decoder and logic that categorizes input months and provides outputs for stock adjustment logic.

Part B: Full adder-based stock calculator to add or subtract stock levels based on month categories and store updated values.

Uses AND, OR, NOT gates, XOR gates, D Flip-Flops, and 4-bit full adders for operation.

# How It Works

Users input the month value (M1, M2, M3, M4) using input pins.

Part A processes the input to categorize the month and detect errors.

Part B uses the categorized month to adjust stock levels in memory, updating the stock dynamically.

An error signal is triggered for invalid months (above 11).

Circuit Templates

4-16 Decoder

Month Logic

Full Adder

4-Bit Full Adder
