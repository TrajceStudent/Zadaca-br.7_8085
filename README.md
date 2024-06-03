# Zadaca-br.7_8085

A multi-processor system consists of 4µP 8085A. One of them is superior to the other three. The parent µP sends a data byte to all subsequent µPs they process it. The superior µP after sending the the data enters IDLE mode and remains for 3.2 msec. Then it polls the result of all 3 µP and compares it. If all 3 results are the same, it lights up green, if they are a different red light is on.




Develop by:

[Trajce Stefanoski ](https://github.com/TrajceStudent)

Microcomputer's systems

**Built With**

This project is built using the following tools:

- [Emu8086](https://emu8086-microprocessor-emulator.en.softonic.com/): Assembler and emulator for the Intel 8086 microprocessor.

**Getting Started**

To get a local copy up and running, follow these steps.

**Prerequisites**

In order to run this project you need:

A working computer
Connection to internet
Setup

**How to Run**

To run the program, you need an 8086 emulator or assembler. You can use emulators like DOSBox or TASM (Turbo Assembler). Here's how to run the program using EMU8086:

1. Download and install Emu8086 from [here](https://emu8086-microprocessor-emulator.en.softonic.com/).
2. Clone this repository to your local machine.
3. Open Emu8086 and load the `palindrome.asm` file.
4. Assemble the code by pressing the Assemble button.
5. Run the program by pressing the Run button or by pressing F10.
