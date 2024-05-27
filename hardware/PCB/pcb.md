# PCB

This directory contains the PCB design files for the ATmega328P-based microcontroller project.

## Files

- `atmega328p_pcb.brd`: The original PCB design file in EasyEDA format.
- `gerber/`: Contains the Gerber files needed for PCB manufacturing.

### Gerber Files

The Gerber files are used by PCB manufacturers to produce the board. The `gerber` directory contains the necessary files

## Viewing the PCB Layout

### EasyEDA Format

The original PCB layout file is provided in EAGLE format. You can open and edit this file using the EasyEDA PCB design software.

1. Download and install [EasyEDA](https://easyeda.com/page/download).
2. Open the `atmega328p_pcb.brd` file in EasyEDA.

### Gerber Viewer

To view the Gerber files, you can use a Gerber viewer such as [Gerbv](http://gerbv.geda-project.org/) or an online viewer like [Gerber Viewer](https://gerber-viewer.easyeda.com/).

## Manufacturing the PCB

To manufacture the PCB, provide the Gerber files in the `gerber` directory to your PCB manufacturer. Most manufacturers accept a ZIP archive of these files.

