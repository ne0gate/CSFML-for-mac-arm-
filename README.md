# CSFML-for-mac-arm-
A public repo that explains how to port CSFML to new arm architecture using rosetta.

First of all if your mac supports the X86_64 architecture do not try this method as it can damage your mac and display drivers.

The new M1-M2 architecture being based on arm cannot run a lot of programs like CSFML or classic compilers like GCC with no tweaks.

Natively arm powered macs dont support emulation and rosetta, you will need to install XCODE and all of its dependencies first. 
