Number Guessing Game in C
----
(meant to teach about raw user input, cmd line interfaces and simple alorithms(my first). also first time using make to build a c program 

how to run it
____
$ make clean
$ make all
$ make run





















http://www-scf.usc.edu/~csci104/installation/gccmac.html (gdb, g++/g++4.8, gcc install instructions)

For Mac:
(Must have brew package manager installed)

	√ brew install gcc (* Takes about 10 - 15 min on school network speed)
	brew install gcc48
	(gcc-4.8 --version)
	

Using g++-4.8:
	
	g++-4.8 test.cpp -o test.out

	* (optional) Tell Bash (~/.bashrc) to run 4.8 (vs default) directly
		
		(put these in ~/.bashrc)
		alias g++="g++-4.8"
		alias gcc="gcc-4.8"

		(then run in cmd)
		source ~/.bashrc

Using gdb (GNU Project Debugger):
	brew install https://raw.github.com/Homebrew/homebrew-dupes/master/gdb.rb
	gdb --version


Compiler options (tested):
	
	g++ ericPhungGuess.cpp 
	gcc pegasusGuess.cpp
	g++ -std=c++0x pegasusGuess.cpp -o pegasusGuess
	make pegasusGuess