# Testing at home

Caia is a system that you can use to test and improve your CodeCup submission from home. Caia is used by both advanced competitors as well as beginners.

You can download Caia and start development today!

## Caia

The Caia Project is the result of the need to have software to play competitions between programmed client players of strategic games from their own homes. That software is now available under a Linux environment.

Jaap Taal and Marcel Vlastuin developed a home edition of the jury software and published it as open source. The project Caia consists of several components:

* The program caiaio, which is written in the language C++. This is the main program that takes care of the input and output and is ready-to-use. Caiaio stands for: Caia-input-output.
* Programs that have to be written by the user are: a manager, a referee and, of course, the players themselves. The referee and the players are game dependent; the manager is not. The programs can be written in any language, you'll just need to provide an executable program. C, C++, Pascal and Haskell programs are typically compiled, Python scripts can use a shebang line. Java programs will need a shell script so that caiaio can start it without parameters. On windows you'll need a small executable for Java and Python scripts, batch files won't work.
* The protocol that explains how the referee, the manager and the players can communicate with the caiaio and the others.
* Ready to use system for this year's competition, including a referee and some test players from the CodeCup site.

For more information please read the full project description.
For a reference about how to install and start Caia please download the tutorial below on this page for your operating system. 

## Competition Manager

The competion manager can organise full competitions. This new manager can replace the normal manager executable if you don't just want to test your program, but with the competition manager you can organise a competition where each of your programs play against all other programs.
The competition manager is included in all distributions of Caia.

## Download

There are five different versions of the Caia-distribution for the game blackhole:

* Linux version (tutorial)
* Linux 64bit version (tutorial)
* Cygwin version (tutorial)
* Cygwin64 version (tutorial)
* OSX version (tutorial)

Our experience with Caia learns that it runs best under Linux. Cygwin under windows is a good alternative. Read more about Cygwin on www.cygwin.com.
Old Caia distributions

The first caia distribution was published in 2004 (CodeCup 2005). This old package (which uses an outdated caiaio) contains examples for the referee and the manager. You can use these examples. It is adviced to replace the caiaio files, which are included in the Caia-distribution for the game of this year.

* Lamistra and Rolit 2005 version (tutorial project documentation)
