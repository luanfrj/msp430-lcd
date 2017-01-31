# MSP430 LCD Interface

This program interfaces an LCD 16x2 with the MSP430 microcontroller.

## How to use
First step is to compile the code:

	make

After done with compilation is needed send the binary code to microcontroller with mspdebug

	mspdebug rf2500

In the mspdebug prompt

	(mspdebug) prog lcd.elf
	(mspdebug) run

That's all