# Eagle-cnc

To make a board through eagle and cnc .. 

you are going to nead 
Eagle to design a Schematic and Board . 
GIMP to start editing the png files you going to have to adjust them to the cnc 
Fabmodules to start extracting rml files for the cnc and adjust values for the pcb and your circuits .

IMPORTANT : 

How fabmodules need files from eagle to can extract pcb right ? ..

2 rml files we get from the fabmodules .. 

first file for the traces .. the cnc is going to engrave the line between black and white . 
second file for the driiling .. the cnc is going to cut the black points or wires . 

Schematics assign orders : 
1) add
2) delete
3) move
4) wire
5) junction 

Board assign orders : 
1) route
2) rip
3) move
4) group

Board design rules : 
1) wire to wire 3 : 5 mm
2) between objects 40 : 60 mil 

Board route values :
1) remeber first from grid to turn all board to mm 
2) width of route .8 for control signals better be 1 mm 
3) width of route 2 mm for power wires

GIMP settings : 
1) canvas size and add 20 pixel for each x and y and centre the png
2) flatten image 
3) colorize to make the selection white 

Fabmodules settings : 
1) every x,y,z make them zero , only zjog let it 2 as it is .
2) number of offsets 2 
3) overlay offsets 20% 




