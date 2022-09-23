# Wii Tennis Game
	A 2 dimensional tennis game created in Python.
	Based on the Nintendo Wii Sports tennis game.

Author: Harry He

## General Information
	- Created December of 2020 as apart of a computer science course.
	- Coded in Python 3.8.5 using Pygame.
	- Attempts to provide a fluid tennis experience in recreating Wii Sports Tennis.

https://user-images.githubusercontent.com/69978107/192068745-bdf301f6-554f-4682-bc72-a28b6ba2ef54.mp4

A video demonstration of how the game is played and some of the features that it provides.

## Installation and Running

	1. Create or open the folder in which you wish to download and run the game.
	
	2. Open the command line at that folder and download the game using the command.
		
		git clone https://github.com/he-is-harry/Wii.git
		
	3. If you do not have python or pygame, continue through these steps, otherwise, you can 
	skip to step 7.
	
	4. Download python from https://www.python.org/downloads/. It may be helpful to click the 
	advanced settings and enter the location where the game is stored from as a virtual environment 
	(this solved a problem when running the game without an IDE).
	
	5. Download the pip package installer from https://pypi.org/project/pip/ OR run the following 
	commands to download.
		
		MacOS: 		$ python -m ensurepip --upgrade
		Windows: 	C:> py -m ensurepip --upgrade
		
	6. Use pip to install pygame, by running the following commands.
	
		pip3 install pygame
		
	7. Open the command line at the folder in which the game is downloaded, then go into the 
	subfolder Wii by running the command.
	
		cd Wii
	
	8. Run the game by running the command.
	
		python3 Main.py
		
If you get the error, ModuleNotFoundError: No module named 'GAME'. Put the entire game into a new folder called GAME. Then, redownload python and click the advanced settings, then click into the virtual environments section. Then, you can add the folder called GAME. This should allow the game to operate correctly. Alternatively, you can change the import statements in all of the files and remove "from GAME", this should also make the game work correctly.
	
**Note**: The game may not work correctly on different operating systems; I personally use MacOS, so the game may not operate correctly on Windows, Linux or other operating systems.

## License

MIT License

Copyright (c) 2022 Harry He

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


This license however, does not apply to the resources associated with the game
(images, font), many of which are copyright and cannot be distributed or used
for commercial use. The resources in the game are under exclusive copyright, so
one cannot copy, distribute, or modify the work without being at risk of take-downs, 
shake-downs, or litigation. These resources are only in use because the project
is of an educational purpose, not being published into the public nor for commercial
gain.

