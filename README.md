# Dig-Deeper
A game made for a game design class.

 _____   _          _____                               
(____ \ (_)        (____ \                              
 _   \ \ _  ____    _   \ \ ____ ____ ____   ____  ____ 
| |   | | |/ _  |  | |   | / _  ) _  )  _ \ / _  )/ ___)
| |__/ /| ( ( | |  | |__/ ( (/ ( (/ /| | | ( (/ /| |    
|_____/ |_|\_|| |  |_____/ \____)____) ||_/ \____)_|    
          (_____|                    |_|                

Programmer: Megan Bond
Contact Me: bond_megan@hotmail.com
Class & A#: CPSC 386 Final Project


	  CONTENTS

    I.    Introduction
    II.   External Requirements
    III.  Setup and Installation
    IV.   Rules
    V.    Features
    VI.   Bugs

I.   Introduction
     Dig Deeper is game written in python, runnable on any system with both python and pygame installed.

II.  External Requirements
     

III. Setup and Installation
     Dig Deeper uses Pygame. Both Pygame and Python 3.4 need to be installed. To run Dig Deeper, navigate to the directory containing Dig Deeper using the terminal and run 'python DigDeeper.py' or 'python3 DigDeeper.py' if you have multiple versions of python installed on your computer.
     

IV.  Rules
     Move using the arrow keys. Use the 'z' and 'c' keys respectively to place supports to the left and right. Use the 'x' to place down a ladder where you are. Cave-ins are caused by digging into the three spaces below a rock or placing a ladder within three spaces below another ladder. Supports prevent these cave ins, if they are placed in the column that is at risk. Reach the bottom row to complete the level, and complete six levels to win the game.

V.   Features
     -Graphics
     -Win Screen
     -Lose Screen
     -Both keyboard and mouse use

VI.  Bugs
     1. Down Checking
        Algorithm for checking if lose state occurs cannot presently detect
        if the lose state occurs when a ladder is placed on top of an already
        placed ladder. This lose state is a tunnel collapse.

     
