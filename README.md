This is a KeyPad, made by Rohan Seshasai Vasa. This is a phase 2 of my button matrix game
I have used 5 switches to make this KeyPad. The switches used is Cherry MX. The reason I made this is that I had made an Arduino game.

Here is the game 
The game name is "Find a path". In this game for the first 5 seconds there will be some red(lava) dots will appear then disappear. After that green dots appear and we need to make a path between the 2 green dots without touching the lava dots(we need to memorize the positions).
So, in this game I used 4 x 4 LED and button matrix, I thought Button matrix has like 16 switches, and even more if I go there will be more like 64 keys. So instead of having that many keys, I will have 5 keys.

Switch 1 --> Up

Switch 2 --> Down

Switch 3 --> Left

Switch 4 --> Right

Switch 5 --> Ok / Start.


First we need to click Start button, then any one green dot glows, then you need to make a path between those 2 green dots using the switches.

These type of PCB's can be done on perforated boards for testing, so I took 5 normal switches and soldered it to the perf boards and it looks like this:

<img width="407" height="545" alt="image" src="https://github.com/user-attachments/assets/f574a65f-6b59-4778-b624-fe3984a01534" />

Backside:

<img width="731" height="558" alt="image" src="https://github.com/user-attachments/assets/01ce1a3f-5962-4d6a-90b3-ea377ab6a9fa" />

Then I connected it to Arduino, changed the code to a KeyPad code and then tested, first I got some errors like mapping but resolved them.

Here is how the PCB actually looks:

Schematic

<img width="489" height="517" alt="image" src="https://github.com/user-attachments/assets/5ceda15e-41ac-4c6d-80d3-f74c5ecc81d0" />

PCB

<img width="599" height="536" alt="image" src="https://github.com/user-attachments/assets/0cf3959f-c2ba-4315-942d-0da3824dbbcf" />

3D model of PCB

Front:

<img width="484" height="440" alt="image" src="https://github.com/user-attachments/assets/8e2172ad-72a3-4b0c-a47f-9122b10f0b1f" />

Back:

<img width="588" height="532" alt="image" src="https://github.com/user-attachments/assets/ac23d433-7b74-4d5d-a882-9183521eedfd" />


**BoM:**

| Item No. | Part Name        | Description              | Quantity | Unit | Total Cost(INR) | Links                                                                                                                                   |
|----------|------------------|--------------------------|----------|------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| 1        | Cherry MX switch   | For pressing(clicky clicky)     | 1 (according to pcs in the link)        | pcs  | 482             | https://stackskb.com/store/cherry-mx-clear-switch-5-pin-pack-of-10/                          |
| 2        | Cherry MX switch Keycaps  | For casing of Switches     | 1 (according to pcs in the link)        | pcs  | 601             | https://www.amazon.in/gp/product/B0D9BRQNWK/ref=ewc_pr_img_2?smid=A4M88SXTNCUDD&psc=1                          | 
| 3        | Header Pins (2.54mm)| For attaching on the PCB         | 1        | pcs  | 135              | https://www.amazon.in/Plated-2-54mm-Header-Single-Straight/dp/B09HGTM3PS/ref=sr_1_5?sr=8-5    |
| 4        | PCB printing service | To order the PCB         | 5        | pcs  | 2510              | jlcpcb.com    |
