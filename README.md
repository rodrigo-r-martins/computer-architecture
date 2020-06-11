Project: Computer Architecture 
 
Goals:
● Understand how a CPU is implemented using Hack HDL.
● Understand Von Neumann Architecture and CPU fetch-execution cycle.
● Learn how to design and implement complex sequential circuits by cascading or laying up small building blocks.

There are two tasks in this project:
● Task 1 is to implement memory, CPU and computer chips. 
● Task 2 is to add some new functionalities to ALU (left-shift and right-shift) and thus support new features of CPU.

Shift operations cause an operand to shift left or right (depending on the opcode). A left-shift of one position moves each bit to the left by one. The low-order bit (the right-most bit) is replaced by a zero bit and the high-order bit (the left-most bit) is discarded. A right-shift of one position moves each bit to the right by one. The low-order bit (the right-most bit) is discarded and the high-order bit (the left-most bit) is replaced by sign bit.
