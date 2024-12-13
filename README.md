# Four-Way-Traffic-Light-Simulation
## Overview

This project simulates a four-way traffic light control system using sequential circuits. The system is designed to manage traffic flow efficiently at a multi-lane intersection, ensuring safety and reducing congestion by utilizing T flip-flops and logic gates.
## Abstract  
The traffic light control system operates based on a predefined sequence of states, permitting safe passage for two opposing directions at a time (e.g., North-South, East-West). The system transitions through states in an orderly manner using:
* <b>T Flip-Flops:</b> To toggle states based on clock pulses.  
* <b>Logic Gates:</b>  AND, OR, and NOT gates implement Boolean logic for controlling signals.  
* <b>State Machine Architecture:</b> Defines state transitions and traffic signal logic.  
Each state activates specific traffic lights, coordinating changes to prevent cross-traffic conflicts and optimize safety and efficiency.
## Circuit Design
* T Flip-Flops: Control the timing and state transitions of the traffic lights.  
* Logic Gates: Implement the Boolean logic derived using Karnaugh Maps to simplify conditions for each light.  
* Traffic Signals: Green, Yellow, and Red lights toggle sequentially for each direction, ensuring safety and smooth transitions.
## Outputs
* Green and Yellow lights toggle for active lanes, while other directions see red lights.  
* Smooth transitions between states with brief yellow-light overlaps signal impending changes.
## How to Use
1. [Download Logism](https://sourceforge.net/projects/circuit/)  
2. Open the trafficlight.circ file in Logisim.  
3. Run the simulation and observe the sequential transitions of the traffic lights.  
4. Analyze the state transitions and logic implementation.  

