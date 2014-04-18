ECE281_Lab5
===========

#PRISM Commands

The PRISM table details the commands that are fetched, decoded then executed. It begins by loading in a value from 
an input. It then adds the input value to another input value. That value is output to port 3. The program then jumps to 
the "loop" section of the program reseting the commands back to the ADDI command if there's a negative number 
in the accumulator. If there isn't a negative number, the program continues to the next jump command which loops at 
the end of the function. 
