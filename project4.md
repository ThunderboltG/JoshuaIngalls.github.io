[Back to Portfolio](./)

Ripple-Carry Adder
===============

-   **Class:** CSCI 330: Computer Architecture
-   **Grade:** B+
-   **Language(s):** Icarus Verilog
-   **Source Code Repository:** [Ripple-Carry Adder](https://github.com/ThunderboltG/RC-Adder)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The Ripple-Carry Adder is a 32-bit adder used for processors. The rippleCarryAdder.v file runs the code to add the two 32 bit integers, while the test program visually demonstrates the tests through the CLI. A fullAdder is included as an include to allow the RCA to work properly.

## How to compile and run the program

How to compile and run the project.

```bash
iverilog -o output rippleCarryAdder.v rippleCarryAdderTest.v 
./output
```

If the programming language does not require compilation, the update the heading to be “How to run the program.” If your application is deployed on a remote service, including instructions on how to deploy it.

## UI Design

The Test program is designed to output to the command line. The program displays the current values of A and B, displays the current Cin value, and the Sum of the ripple-carry adder.

![screenshot](rca/rcatest.png)  
Fig 1. The Ripple-Carry Adder

For more details see [Ripple-Carry Adder](https://github.com/ThunderboltG/RC-Adder).

[Back to Portfolio](./)