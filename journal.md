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

**Day 1 (3rd session) - Designing the CAD or casing** _Hours spent: 2 hours_
For this keypad I thought of making casing for it. It was my first time making a CAD, so I used Tinker CAD to do it.
I took a square block and then started to shape it. I tried covering the PCB.

It looked like this:

<img width="528" height="389" alt="image" src="https://github.com/user-attachments/assets/65408b9d-6783-43d3-80a9-bfa54d8b0091" />

I know that it looks unprofessionalistic and made from Tinker CAD.
Then I realised how am I even gonna place a PCB inside it breh. So I tried separating the lid, which eventually works.
Front side:

<img width="607" height="374" alt="image" src="https://github.com/user-attachments/assets/db1dcf54-0570-4ec8-ad39-88207c03074b" />

Back side:

<img width="825" height="460" alt="image" src="https://github.com/user-attachments/assets/8d8ee5e6-9409-4c17-b020-e1aecd771f30" />

Woah why does the lid looks like a minecraft's creeper face lol.
