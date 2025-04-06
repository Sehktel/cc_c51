# Introduction to Clojure Compiler for C51

Clojure Compiler for C51 (CCC51) is an Educational Project.
## Target 
	AT89S4051:
	8051-based 6-cycle microcontroller.
	15 Programmable I/O Lines, Enhanced UART,
	Enhanced SPI interface,  Watchdog Timer,
	Analog Comparator,  4-level Interrupt Priority
	Two 16-bit Enhanced Timer/Counters with 8-bit PWM
	Low Power Idle and Power-down Modes,
	Brown-out Detector and Power-off Flag
	4 KBytes Flash ROM
	256 Bytes RAM

## Input
	C code with some restrctions and adoptations.
	First off all we haven't Floationg point module,
	Trehere for wee haven't single and double types.
	We haven't malloc and free functions.
	We have 'interrupt' function.

## Output
	Binary Code in IntelHex format
	ASM code in .asm files
	AST in .ast files
	Object files in .o files

## Updates
	Checkout cc_c51 project. 
	
	@Sehktel

