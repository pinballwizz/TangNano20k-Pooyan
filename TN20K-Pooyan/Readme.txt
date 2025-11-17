Pooyan Arcade for the Tang Nano 20K FPGA Dev Board. Pinballwiz.org 2025
Code by DarFPGA.

Notes:
Setup for keyboard controls in Upright mode (5 = Coin) (Start P1 = 1) (Start P2 = 2)(LCtrl - Fire)(Arrow Keys = Move L or R or U or D)
Consult the Schematics Folder for Information regarding peripheral connections.
Consult the Schematics Folder for Information on Tang Nano 20K Internal Clock setup.

Build:
* Obtain correct roms file for Pooyan (see scripts in tools folder for rom details).
* Unzip rom files to the tools folder.
* Run the make pooyan proms script in the tools folder.
* Place the generated prom files inside the proms folder.
* Open the TN20K-Pooyan project file using GoWin.
* Compile the project updating filepaths to source files as necessary.
* Program Tang Nano 20K Board.
