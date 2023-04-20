# VHDL_GuitarHero
The purpose of this project is to recreate the guitar hero video game in an FPGA using VHDL. This will be done by using VGA to display the game, and using the four buttons on the DE2-115 board to control the game. The actual game will consist of 4 rows of notes approaching the bottom middle of the screen, corresponding to the four buttons on the DE2-115 board. When the user starts the game by pressing any button, different notes will scroll down the screen and the user must press the corresponding buttons at the same time as when the note crosses a certain threshold. The song that the notes correspond to is the ABCs. If the player hits the note correctly, the game will increase the score of the player by one. This score will be displayed on the 7 segment display while the game is going along, showing your final score at the end. :)

To get the game running in Quartus, open up the vga_with_hw_test_image.qpf file in quartus and program the fpga using that file, it should autofill the file to upload using the programmer.

Demonstration: https://youtu.be/QmWoFfy1oiU
