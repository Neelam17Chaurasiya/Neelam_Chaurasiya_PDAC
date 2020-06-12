.title KiCad schematic
.include "E:\KICAD\lib\ngspice\MOS\NMOS-180nm.lib"
.include "E:\KICAD\lib\ngspice\MOS\PMOS-180nm.lib"
R1 Net-_R1-Pad1_ Net-_M3-Pad3_ 1k
R2 Net-_M3-Pad3_ Net-_M5-Pad3_ 2k
M5 Net-_M11-Pad3_ A0 Net-_M5-Pad3_ Net-_M5-Pad3_ CMOSP
M11 VOUT Net-_M11-Pad2_ Net-_M11-Pad3_ Net-_M11-Pad3_ CMOSP
V2 A0 GND dc 5 pulse(0 5 1p 1n 1n 50n 100n)
M2 Net-_M1-Pad1_ A0 GND GND CMOSN
M1 Net-_M1-Pad1_ A0 Net-_M1-Pad3_ Net-_M1-Pad3_ CMOSP
R3 Net-_M5-Pad3_ Net-_M7-Pad3_ 2k
R4 Net-_M7-Pad3_ Net-_M10-Pad1_ 2k
R5 Net-_M10-Pad1_ GND 1k
M7 Net-_M10-Pad3_ Net-_M1-Pad1_ Net-_M7-Pad3_ Net-_M7-Pad3_ CMOSP
M9 Net-_M10-Pad3_ A0 Net-_M10-Pad1_ Net-_M10-Pad1_ CMOSP
M13 VOUT A1 Net-_M10-Pad3_ Net-_M10-Pad3_ CMOSP
V4 A1 GND dc 5 pulse(0 5 1p 1n 1n 100n 200n)
M16 Net-_M11-Pad2_ A1 GND GND CMOSN
M15 Net-_M11-Pad2_ A1 Net-_M15-Pad3_ Net-_M15-Pad3_ CMOSP
V1 Net-_R1-Pad1_ GND dc 5
V3 Net-_M1-Pad3_ GND dc 5
V5 Net-_M15-Pad3_ GND dc 5
M3 Net-_M11-Pad3_ Net-_M1-Pad1_ Net-_M3-Pad3_ Net-_M3-Pad3_ CMOSP
M14 Net-_M10-Pad3_ Net-_M11-Pad2_ VOUT VOUT CMOSN
M12 Net-_M11-Pad3_ A1 VOUT VOUT CMOSN
M10 Net-_M10-Pad1_ Net-_M1-Pad1_ Net-_M10-Pad3_ Net-_M10-Pad3_ CMOSN
M8 Net-_M7-Pad3_ A0 Net-_M10-Pad3_ Net-_M10-Pad3_ CMOSN
M6 Net-_M5-Pad3_ Net-_M1-Pad1_ Net-_M11-Pad3_ Net-_M11-Pad3_ CMOSN
M4 Net-_M3-Pad3_ A0 Net-_M11-Pad3_ Net-_M11-Pad3_ CMOSN
.end
