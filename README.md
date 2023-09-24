# EuristicSequencer
8 step sequencer based on probability and locking the bits you like. Prototyped with Arduino.

# Useful Resources
-Reading Clock from MIDI:
https://forum.arduino.cc/t/read-midi-clock/1022060/14

-Logistic function:
https://en.m.wikipedia.org/wiki/Logistic_function

# Project Plan
Mark I
1) Read Clock from MIDI
2) Generate random CV every Clock
3) Implement 3way switch from low-mid-high random CV range
4) Implement Mute for each step
5) Implement locking of the random CV
6) Implement triplets on button switch
7) Generate Random Lenght CV
8) Generate CV based on Logistic Function
9) Add probability based Lenght (the goal is to generate random patterns that always fill 4/8 bars I suppose)
10) Have fun playing it, this is mode I

Mark II
1) Add rotary switch that limits to a number of steps (maybe add LCD)
2) Implement mode LIMIT L (every note is adjacent to the mext one, but the loop waits the measure)
3) Implement mode FILL F (there's only one note in each step, the thing that changes is the placement within the step)

# Components
- Soldering Tools
- Electrical Cables/PCB
- 1x MIDI socket
- 1x Arduino Board
- 8x Switches (lock)
- 8x Push button (mute)
- 8x Toggle switch (triplets)
- 1x Potentiometer (randomness)
- 1x 3 way switch (Random Range)		
- 2x 3.5 audio sockets (CV and Gate Output)
- 8x LED (current note indicator)
- STUFF for standalone alimentation!!!


