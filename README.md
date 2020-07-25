# Digital-Logic
This repository is for PCBs related to digital logic.
To build these PCBs, we used Autodesk's EAGLE, a CAD software for making schematics and board files. All of the files you see ending in .brd are "Board" files, which show what the board connections, shapes, and layers actually look like.

## Single Transistor Board
This board file is meant to emphasize a single transistor and act as a breakout board for its 3 pins. These pins each serve a distinct purpose:
- **Signal Pin**: this pin is where you send an input current or voltage signal to a transistor.
- **Output Pin**: this pin is where your output current comes from. If you are using a BJT transistor, this is how you amplify current. For MOSFTETs, this is how you amplify voltage signals.
- **Power Pin**: this pin is where you are supplying voltage to the transistor. If the voltage is too low, you won't be able to see any amplification of your signal.

## Logic Gates
These PCBs are meant to be assembled such that you can perform AND, OR, and NOT operations. They are shaped to look like their symbol representations. The transistors used are MOSFETs and are labeled as N or P channels where appropriate.

## RS-Latch
This is the smallest unit of memory in computing. Instead of trying to use entire transistors to make the gates that make the RS-latch, we use a Quad-NAND logic gate IC to make the connections. The 1 pin is marked by a small white outline of a circle. R, S, Q and !Q are labeled on their appropriate prong of the PCB.
