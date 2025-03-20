# Traffic-Light-Controller-using-Verilog
Introduction

Traffic control is a challenging problem due to the high number of vehicles and the dynamic nature of traffic systems. This project focuses on implementing a traffic light controller for a T-shaped road using Verilog HDL. Verilog is chosen because it simplifies circuit design, debugging, and simulation, overcoming the limitations of manual circuit connections on breadboards or PCBs. The project is simulated using Xilinx 14.5 to validate the traffic light control logic.

Methodology

Directions Considered

The traffic system consists of four directions: M1, MT, M2, and S. Six states (S1 to S6) are defined based on these directions. The system follows a finite state machine approach to control traffic light transitions.

Problem Statement

Green Light: Indicates free vehicle movement.

Red Light: Indicates stop due to traffic.

Yellow Light: Indicates medium traffic flow.

State Diagram

The state transitions are based on the following time delays:

TMG = 7s

TY = 2s

TTG = 5s

TSG = 3s

Each state transitions to the next based on these predefined time delays, ensuring an efficient traffic flow cycle.

State Table

Each state defines the signal conditions for M1, MT, M2, and S, ensuring synchronized traffic management.

RTL Code

RTL Schematic View

The RTL schematic shows the structural implementation of the traffic controller module, mapping inputs and outputs efficiently.

TESTBENCH

Output Waveforms

The output waveforms verify the correct state transitions and light activations as per the designed time delays.

Result

The Verilog-based traffic light controller successfully manages traffic flow for a T-shaped road, optimizing signal timings using FSM logic.
