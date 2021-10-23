# Farini-VC-ADSR

![Farini Photo](/Docs/Farini-Photo.png)

Voltage controlled AD / ADSR

- Envelope generator switchable between ADSR & AD
- Loopable
- End Of Cycle output
- Output can be inverted for ducking


- When in AD mode use the trigger input
- When in ADSR mode, use the gate input to start envelope, the trigger input will retigger the attach phase
- When in cycle mode use no inputs

 Contained are schematics & gerber files for pcb fabrication of both electrical and front panel. This is sutiable for entry level however a basic level of electronics, soldering, fault finding, and some basic tools are required.
 
 
 [Schematic](/Docs/Farini-Schematic.pdf)
 
 [BOM](Docs/Farini-BOM.pdf)
 
 
 If you wish to edit in ki-cad the following dependencies are required, however the component values will need tidying on the PCB as I use a forked version with no values.
 
  https://github.com/holmesrichards/Kosmo_panel
  
  https://github.com/holmesrichards/aoKicad