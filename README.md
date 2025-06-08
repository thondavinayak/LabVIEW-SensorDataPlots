# LabVIEW-SensorDataPlots
Plotting of Sensor Data and visualizing in LabVIEW

This repository contains a set of LabVIEW Virtual Instruments (VIs) developed to practice core concepts in graphical programming, focusing on loops, temperature monitoring, mathematical operations, and state machines.

Exercise Overview
1️⃣ Combo While-For Loop (whilefor.vi, whilefor2.vi)
Objective: Create a VI that behaves like both a While Loop and a For Loop.

Details:

Use only a While Loop.

The loop terminates either when the maximum iteration count is reached (specified by a front panel control) or when the user clicks the Stop button.

2️⃣ Temperature Monitoring (temperaturemonitor.vi, temperaturelimit.vi, thermometer.vi, thermometerstart.vi)
Objective: Continuously monitor and display temperature readings.

Features:

Temperature measurements every second.

Display on a scope chart.

LED indicator activated when temperature exceeds user-specified upper/lower limits.

Front panel controls to adjust temperature limits.

Additional VIs (thermometer.vi, thermometerstart.vi) explore different visualization and data presentation techniques.

3️⃣ Temperature Min & Max (temperaturemonitor.vi)
Objective: Extend the temperature monitoring VI to track maximum and minimum temperatures.

Details:

Utilize Max & Min functions and shift registers.

Real-time updates of the highest and lowest recorded temperatures.

4️⃣ Square Root Calculation (squareroot.vi, squarerootcalc.vi, formulanodeexercise.vi)
Objective: Create a VI to compute the square root of a user-specified number.

Key Requirements:

Use a Formula Node instead of a Case Structure.

If the user enters a negative number, the VI outputs an error code -99999.

Additional VIs (formulanodeexercise.vi, squarerootcalc.vi) provide variations of this implementation.

5️⃣ State Machine (FSM.vi, shiftreg.vi, randmatcher.vi, randaverage.vi)
Objective: Build a basic State Machine to illustrate state transitions.

Implementation:

Uses While Loops, Case Structures, and Enums for state handling.

LED indicator on the front panel shows the current state.

State transitions are controlled by a front panel button.

Variants like randmatcher.vi and randaverage.vi further explore data-driven transitions.

6️⃣ Array Operations & Clusters (arraypairmult.vi, arrayplot.vi, clusterarrayformula.vi, clusterarrayformulaexercise.vi)
Objective: Practice array manipulation and cluster operations.

Details:

arraypairmult.vi: Multiplies elements from two arrays in pairs.

arrayplot.vi: Visualizes array data using plots.

clusterarrayformula.vi and clusterarrayformulaexercise.vi: Apply mathematical formulas to cluster data.

7️⃣ Miscellaneous VIs
Random Functions:

randaverage.vi, randmatcher.vi – Explore random number generation and comparison.

Other Practice VIs:

15thermocluster.vi – Possibly a cluster-based temperature VI.

formulanodeexercise.vi – Practice using Formula Nodes.

shiftreg.vi – Shift register demonstration.

Getting Started
Prerequisites:

LabVIEW installed (version compatible with these .vi files).

Running the VIs:

Open LabVIEW.

Open any of the .vi files and run them using the LabVIEW interface.

Adjust front panel controls as needed to test behavior.

Folder/File Summary
File Name	Description
15thermocluster.vi	Cluster-based temperature monitoring example
arraypairmult.vi	Pair-wise array multiplication
arrayplot.vi	Array data plotting
clusterarrayformula.vi	Cluster and array formula application
clusterarrayformulaexercise.vi	Exercise variant for cluster/array operations
formulanodeexercise.vi	Exercise for Formula Node usage
FSM.vi	Basic finite state machine example
randaverage.vi	Random number averaging demonstration
randmatcher.vi	Random number matching demonstration
shiftreg.vi	Shift register demo
squareroot.vi	Square root calculator with error handling
squarerootcalc.vi	Variation of square root calculation
temperaturelimit.vi	Temperature monitoring with limit checking
temperaturemonitor.vi	Full-featured temperature monitoring
thermometer.vi	Thermometer style VI
thermometerstart.vi	Start-up thermometer display
whilefor.vi	Combo while/for loop exercise
whilefor2.vi	Variant of the while-for combo loop
