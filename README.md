# teensy4.1-daughtercard


* Goal: Connect GigaPCB female connector (XG4H-5031) onto a Teensy 4.1 daughtercard.
* Solution: Use a male connector (XG4A-5034) to link GigaPCB to Teensy 4.1 MCU.

**ALL PLANNING INFORMATION AND PIN WORKS CAN BE FOUND HERE: https://docs.google.com/spreadsheets/d/1IKXbfIiIrP6nyM8Mc0eolMKgb26c2Qc9dl-_x0jVvCI/edit?usp=sharing**

Revisions after Design Review #1 (6/11)
* Added a 3v3 LED to indicate good board connection
* Made TX+/TX- and RX+/RX- differential pairs with matched lengths
* Added GND vias across the board
* Made it a four layer board (signals -> ground -> power -> signals)

Contains the daughtercard housing the Teensy4.1 MCU used for the GIGAPCB architecture for Texas A&amp;M Rocket Engine Design. An Standard Operating Procedure (SOP) will be provided for assembly/use instructions.
