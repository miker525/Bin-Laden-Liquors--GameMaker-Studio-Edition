## Summary

What you have here is an open source Game Maker: Studio based version of the old early 2000's online Flash game Bin Laden Liquors. This project is based on the original game by Keith E. Fieler and can be played online at: http://www.flashrolls.com/shooting-games/Bin-Laden-Liquors-Flash-Game.htm . All assets used in this Game Maker: Studio project were ripped directly from the flash version of the game and thus I am not claiming ownership over them. All code used within the game was however written by me. There are a number of changes to the gameplay itself including Scaling difficulty (starts easy and progressively gets more difficult the more terrorists you kill), scoring differences (changed the values of each kill to 100 points per terrorist kill or minus 1000 points for a hostage kill) as well as changes to how the game ends (game will end if you miss 10 terrorists or if you kill 5 hostages). The menu has also been changed ever so slightly. Additionally my version isn't 100% complete as it is missing many sound effects from the original flash version of the game. These may be added in later on, but for now the project should be assumed to be done. I created this clone project as a small way for me to learn the basics of Game Maker: Studio so don't expect any kind of real updates to this. If anyone is interested however they may feel free to fork it or push changes to the game.

## How to use

Included in this repository is the source code for the project (all code and assets), as well as executable versions of the game for Windows and Ubuntu. If anybody would like to go about building an OSX version feel free to push it to the git. The source code can be opened by importing the .gmx directory into Game Maker:Studio. The executable can be run on Windows by entering the bin directory and double clicking the .exe file. The Ubuntu version can be run by double clicking the .deb file in the bin directory.

## Motivation

Why bother to make a clone of this old flash game that nobody cares about? Well recently I've been delving into all different game engines, learning how they work and testing their capabilities as well as comparing the 'major' game engines to writing my own. During the recent Humble Bundle sale I picked up a copy of Game Maker: Studio Pro and wanted a basic project to test out the engine. This old flash game felt perfect for cloning because it has basic features like saving/loading from files, random number generation and a series of other small systems that would be essential for larger projects. 

## Post Opinion on GameMaker: Studio

My overall opinion of the engine after building this project is that it's amazing for small 2D based games, or quickly throwing together prototypes. It's very quick to put working games together and it's ability to build for just about any platform along with it's low cost make it a great competitor however  it's custom language (GML) is very strange. The inability to create things like classes or even functions in code are a big downer. The room editor and sprite editor are pretty bad. Overall it's still missing quite a bit but I'm impressed with how quickly I can get stuff done in it.

## Documentation

Most of the code in the project is commented telling users what exactly the code is doing. Reading the comments should help you trace back everything to find exactly the spot you need. For code that isn't commented it's because I felt it was so self explanatory it didn't need comments. If you're confused about any of this feel free to reach out and I can help you. Because this was my first GMS project some things are done pretty horribly. I know this. Some things were fixed to make more efficient. Some stayed bad because, quite frankly it doesn't matter. This was a small experiment not designed for profit so some things can stay strange. An example of this terribleness is how the Desk object is what spawns the hostages!

## Bugs

As of right now I don't have any known bugs. I believe I got rid of any bugs I noticed while putting the project together. Of course there is always a chance I missed some. Feel free to submit issues to the project if you notice bugs. I may or may not fix them, but even if I don't someone else may be interested in doing so.

## Contributors

Michael Rosenberg (a.k.a. Mike Rosenberger, a.k.a. Miker525) - Developing the Game Maker: Studio version of the game. Made this git repo. Ripped the assets. Put the thing together!
Keith E. Fieler - Developer of the original Flash game over 10 years ago! 

## License
The code for this project is being licensed under the MIT license. As I've stated above I do not claim ownership over the project assets.

Copyright (c) 2015 Michael Rosenberg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.