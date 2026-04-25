**Day 1 (1st session) - Getting the schematic** _Hours spent: 3 hours_ 

Today I wanted to build a Keypad for my Arduino game.
For that I opened KiCad created new project and opened the schematic editor. Today instead of wiring things up I used net labels to keep it clean.
First I added 5 switch(It is a 5 switch keypad) and named them _Up, Down, Right, Left and Ok_. Then used 01 x 06 Socket pin header. Then used net labels to connect all the switches. Also instead of having many GND's I wanted to use B.Cu to create filled zones.

Then I ran an ERC and got an error which stated that there was not way of power to the GND. So, I used PWR_Flag for a clean ERC.

It looks like this:

<img width="452" height="527" alt="image" src="https://github.com/user-attachments/assets/98ef0401-c615-43f7-b49c-690223014fa6" />

**Day 1 (2nd session) - Designing the PCB** _Hours spent: 4 hours_

Assigned the footprints for the symbols. Here I used the _Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB_ footprint for Switches.

I positioned the switches and Headerpins to right place and started route them one by one. I chose B.Cu layer and then drew filled zones all over the PCB. Used vias for better copper pours too! Also for the outline used Edge.Cuts. For labelling used B.Silkscreen and mirrorized them.
Here is the PCB.

<img width="575" height="513" alt="image" src="https://github.com/user-attachments/assets/715f0de4-c5d6-410e-8e78-d02ff95d6be0" />

**Day 1 (3rd session) - Designing the CAD or casing** _Hours spent: 4 hours_
