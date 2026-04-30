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

THese type of PCB's can be done on perforated boards for testing, so I took 5 normal switches and soldered it to the perf boards and it looks like this:

Then I connected it to Arduino, changed the code to a KeyPad code and then tested, first I got some errors, like mapping but resolved them.
