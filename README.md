# HappyFeet-s-VRift-Simulator
A simulator for MouseHunt's Valour Rift. It draws upon a database of mouse data, in order to simulate each hunt in the Tower, with all Tower upgrades and relevant augmentations included. Bulwark of Ascent, Terrified Adventurer, and Eclipse mice are all accounted for, in terms of their special effects. Once a new floor is reached, the pool of mice automatically adjusts for floor specific mice, as these vary in their catch rates between floor types. There is also an option to toggle using the Ultimate Charm only for Eclipse Floor mice.

Using the Simulator:

The beginRun() function of the VRift class allows for a single run, returning the floor reached, eclipse reached and hunts taken. 
The collectData() function performs a number of VRift runs (placed in the function argument) and generates basic statistics based on them at the end.

Credits to tsitu for the CRE data and formula. The relevant github page is linked here: 
https://github.com/tsitu/MH-Tools

For more details, refer to the reddit post here:
https://www.reddit.com/r/mousehunt/comments/mn7y5n/happyfeets_valour_rift_simulator/

Happy Hunting!
