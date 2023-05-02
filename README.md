Download Link: https://assignmentchef.com/product/solved-col216-assignment7-software-simulator-in-c-for-the-mips-processor
<br>
<strong>Statement</strong>

In this and the subsequent assignments, you will build a software simulator in C++ for the MIPS processor.

<ol>

 <li>The input to your program is a MIPS program (limited to the instructions you have already implemented in previous assignments). Read this input into an array of instructions.</li>

 <li>Simulation starts with the Program Counter (PC) pointing to the first instruction.</li>

 <li>Execute the instruction. Display the values of the Register File and Memory contents as a result of executing the instruction.</li>

 <li>Proceed to the next instruction and continue the execution.</li>

 <li>Simulation stops when there is no further instruction to execute.</li>

</ol>

This version of the processor is a <strong>MULTICYCLE</strong> design (not PIPELINED). Assume that you will be given a file that indicates the information of how many clock cycles each instruction requires.

At the end of execution, print out statistics about the clock cycle counts and average Instructions Per Cycle (IPC) for the input program.

A sample input file with delay values of each instruction is as follows:

add 4 sub 4 beq 5 …etc.