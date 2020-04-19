GnuWin32 Make tool version 3.81

Make is a tool which controls the generation of executables and other non-source files of a program from the program's source files. Make gets its knowledge of how to build your program from a file called the makefile, which lists each of the non-source files and how to compute it from other files. When you write a program, you should write a makefile for it, so that it is possible to use Make to build and install the program.

Attached a "makefile" example that came from WinAVR Toolchain. This makefile is very complete but other templates could certainly be used. However, in order to use this makefile

C:\Program Files\Git\usr\bin

must be in the system variables %PATH%, since this makefile template uses commands such as rm.exe and cp.exe.