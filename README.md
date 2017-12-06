# ECE287_Final_Project

Introduction
	Our final project for ECE 287 is a Tic Tac Toe game written in VHDL and suited for an Altera DE2-115 FPGA. The monitor used to display our VGA has a resolution of 1280 x 1024 pixels and a 60Hz refresh rate. It is controlled by switches SW0 to SW17 on the Altera board. Each switch designates a single move in a single square on the tic tac toe board; switches SW17 through SW9 control player one’s moves, while switches SW8 through SW0 control player two’s moves. Player one’s moves are represented by cyan squares, and player two’s moves are represented by magenta squares. The tic tac toe board is white until a player wins. When a player wins, the board changes its color to the color of the winning player. 

