# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-24 at 1 16 34 PM](https://github.com/user-attachments/assets/6b91d83a-aee6-4bd0-a984-4e9f75212475)


#### Area report:
![WhatsApp Image 2024-11-24 at 4 27 20 PM](https://github.com/user-attachments/assets/0c76f1dc-b63c-412a-ab98-e8fa4f6aa50c)


#### Power Report:
![WhatsApp Image 2024-11-24 at 4 27 43 PM](https://github.com/user-attachments/assets/d9d34654-e6ab-4b09-ac62-0426d2abccf6)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
