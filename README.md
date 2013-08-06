launch4j
========
A mirror of
:pserver:anonymous@launch4j.cvs.sourceforge.net:/cvsroot/launch4j launch4j

My fork
-------
This fork exists to demonstrate how to modify the code so that the gui version of the wrapper can still attach to the console of a parent process, and write stdout to there.

This has the benefit of not creating a new console when the .exe is launched directly from Explorer (or any other gui based application), while still functioning as a command line based tool as well (printing output to the console).
