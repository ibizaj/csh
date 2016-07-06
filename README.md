# how to create a cmd under csh shell
* Create a directory say "bin" under your home directory.

* Update your path variable to include this bin directory. Put this in .cshrc file to make it permanent.
	
		setenv PATH $PATH\:$HOME/bin
  
* Create a script say, "hello" and keep it in your bin directory. Give execute permission to the hello script.


		#!/usr/bin/perl -w    
		print "Hello\n";

* From any directory, you simply type:
	
		$ hello
		Hello

