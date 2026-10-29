#### problems with circuit 10-23

* ELIMINATE REGULATOR. got wayyyy too hot. switch to buck converter for sure.
* Have larger Keep Out Area for the mounting holes. Ended up shorting to plate week before submission
* On the Muon Detector circuit from MIT, they have a boost converter going to the SiPM board. I chose to remove this, as the boost was achieving ~28V, which is what was provided by Wallops in 2026.
* If memory serves, the only components i had to find replacements for on the Muon Detector circuit were the 2 Schottky diodes. Ensure this is the case before continuing. 
* We had different infrastructure leading to the Pins on the left hand side of the schematic being useful for us. This board was intended to control ALL of our experiments. I can almost guarantee it will not be the same for you. I suggest replacing them with a more relevant design. 
* I have 1, and you have several of the unpopulated control boards to mess with for testing. I also have the version that flew. 
* If MCU is changed, ensure logic levels match.
* I Understand there are no electrical engineering students on the team, but that some of you have PCB Design experience. If you have any questions, please do not hesitate to ask. 