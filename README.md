# Name : GOPINATHAN P
# Reg no :212222060068
# Exp-6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :![Screenshot (55)](https://github.com/user-attachments/assets/6c73be06-d83f-4598-a685-584491483175)


#### Area report:![Screenshot (56)](https://github.com/user-attachments/assets/88889e73-1e33-4762-af2c-38832a439f33)


#### Power Report:![Screenshot (57)](https://github.com/user-attachments/assets/3f95374e-d905-49a7-a103-df1db4d8b265)


#### Timing Report:![Screenshot (58)](https://github.com/user-attachments/assets/b1c3e4ea-d665-4503-b6c5-6ce35d40f2d7)



Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
