## 24-Hour Logic Clock Using Logic.ly ##
=========================================

## Creator ##
==============

Timothy Kosinski

As the sole creator of the 24-Hour Logic Clock, I have applied and demonstrated my skills in digital logic and circuit design. This project is a testament to my passion for Embedded Systems and Software Engineering, showcasing my commitment to creating functional and educational digital models. Drawing on the experience and concepts learned in my college coursework, particularly CSC 3100 - Computer Architecture and Organization, I have created this circuit to showcase the principles of efficient design and logical structuring. 

## Project Overview ##
=======================
This project is a 24-hour digital clock developed using only logic gates in logic.ly. The clock accurately tracks hours, minutes, and seconds, demonstrating the application of digital logic principles in real-world scenarios.

## Features ##
===============
- Displays time in a 24-hour time format
- Accurate tracking of hours (0-24), minutes (0-60), and seconds (0-60)
- Built using Mealy Finite State Machine (FSM)
- Utilizes 4:1 Mulitplexers for input selection
- Debugging Switches for troubleshooting
- Binary-based light bulb display for visual time representation

## Tools and Technologies ##
=============================
- Logic.ly software
- Digital logic gates (AND, OR, NOT, etc.)

## Circuit Design ##
=====================
- The clock's design revolves around an FSM with 3 main decoders for timekeeping. The decoders connect to multiplexers, which initially set the clock to 0. Upon activation, these decoders cycle through various states until they revert back to zero, with each cycle being recorded by registers. The circuit can be activated manually or by a built-in timer. In case of anomalies, debugging tools including multiplexers and a reset button help troubleshoot and reset the circuit to its initial state. 

Included Components:

18 x 4:1 Multiplexers
3 x FSM Decoders for Seconds, Minutes, Hours
3 x 6-Bit Registers
2 x Custom Comparitors for transitioning between time units
3 x Clocks for timing
3 x Switches for debugging and time control 
7 x Buttons for manual adjustments and resetting
36 x Light Bulbs for time display 

## Installation and Setup ##
=============================
1. Download and install Logic.ly on your computer.
2. Clone the project repository from GitHub: https://github.com/TKosinski24/24HourLogicClock
3. Open the .logicly file in Logic.ly.

## Usage ##
============
To start the circuit, ensure the simulation is enabled in Logic.ly. Follow these steps:

1. Confirm the Automatic Timer is OFF.
2. Set Switches A and B to ON and press RESET multiple times.
3. Switch A to ON and B to OFF for Ready state.
4. Begin the circuit if no anomalies are detected.

NOTE: Avoid moving components or spamming the Add buttons, as this can disrupt the circuit

## Visualization and Debugging ##
==================================
- The circuit is labeled for easy understanding, with procedures for handling anomalies.

Debugging Steps:
1. Deactivate the Automatic timer (State OFF)
2. Set Switches A and B to ON.
3. Press RESET mulitple times for a full reset.
4. Switch A to ON and B to OFF for the READY state.

NOTE: For section-specific debugging, set A to ON and B to OFF, and use the corresponding Add button. 

## Challenges and Solutions ##
===============================
- Developing the decoders was a significant challenge, requiring the creation of a truth table, and the creation of 12 different 6-bit K-maps. The complexity of connecting these decoders and transitioning smoothly between bits was addressed using registers and clocks. A custom comparator was implemented to manage transitions between time units. 

## Future Enhancements ##
==========================
- Planned improvements include reducing the number of multiplexers, adding a digital display for easier time reading

## Intent of Purpose ##
========================
- This project is intended solely for demonstrating skills on a resume and is not designed for practical application or reproduction!

