ECE281_Lab5
===========

#PRISM Commands

The PRISM table details the commands that are fetched, decoded then executed. It begins by loading in a value from 
an input. It then adds the input value to another input value. That value is output to port 3. The program then jumps to 
the "loop" section of the program reseting the commands back to the ADDI command if there's a negative number 
in the accumulator. If there isn't a negative number, the program continues to the next jump command which loops at 
the end of the function. 

#Demos
Demo one completed: 22 April 2014
Demo two via Youtube
    https://www.youtube.com/watch?v=XzrX1Z0mzSE 
    
Demo two notes: Couldn't get VHDL to program Nexys board with PRISM program; video contains simulation from PRISM

#Questions

1. When the controller's current state is "FETCH", what is the status of the following control lines:
a. PCLd
b. IRLd
c. ACCLd

2. The current state of Decode LoAddr and the IR contains "OUT". What are the control signals asserted, and what will the next state be?
3. What are the three signals sent from the PRISM datapath to the PRISM controller?
4. Why is it important that ACCLd signal be active during the execute stage for the ADDI instruction?
5. What changes are necessary to the PRISM datapath to add another instruction to the instruction set?




#Documentation
  C3C Erik Thompson helped me via email by suggesting ways to reset the tens place and how I might be able to fix the VHDL issue. 
  
  
  
