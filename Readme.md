Aim of project: 10bit potentiometric DAC 3.3v analog voltage, 1.8v digital voltage and 1 off-chip external voltage reference@osu180nm
•	Design of PDAC
•	Set Up for Simulation
•	Set Up for Generation of netlist Spice Code
•	Contact information
1. Design of Pdac
This Project focuses on designing of potentiometric DAC(Digital to Analog Converter) where digital binary is given as a input and coressponding analog voltage is obtained.In this project Resistor String DAC topology is used to design PDAC.
2. Set Up For Simulation
Ki cad is open source tool (GPL) integrated package which helps to draw a schematic and obtained pcb layout.For simulation of this project firstly install ki cad for windows,macros etc. according to device.
Simulation steps of ki cad on windows are as follows.
1.Install ki cad from given link  On Windows, and other Linux distributions: https://www.kicad-pcb.org/ and download and install KiCad.
2.select CERN switzerland 
3.Run " kicad.exe, a main window will pop up.
4.Create a new project: “File” -> “New”->  “New Folder” button, and name the new folder.
5.. Open the new folder by double clicking on it and Enter the name of the project in “File name”.  now click on open a kicad window will open.
6.Click on the Schematic editor button a  “EESchema” window opens here draw the schematic by  clicking on the “place a components” button found in the right toolbar and make connection by selecting wire from right toolbar.
7. enter the values of the component Right click in the middle of the component and select “Edit Component” -> “Value”.
8. For mosfets go to" spice edit model-->select library of 180nm having extension of .lib.
9. Once schematic is done ,save the schematic project: by clicking on the “File” -> “Save Whole Schematic Project" from left corner of the tool baar.
10.The components now need to be given unique identifiers. To do this click on the
“Annotate schematic” -->“Use the current page only” -->“Annotation"-->"OK"
11.Click on the “Schematic Electric Rules Check” -->"Run",  check the warning and errors. and correct the errors if found.Again save schemetic as mentioned in step no. 9.
12.Now for simulating the schematic click on" Tools"-->"Simulator"-->"setting"-->"transient analysis"-->"OK"-->" Run/simulate"--> Add signal",Select input bits and output voltage equation , observe the waveforms.
