# 2-bit-full-adder
In this project, I built a 2-bit full adder in Tinkercad using only discrete components, without any logic ICs.
The circuit implements the required logic functions (XOR, AND, OR) using a total of 22 NPN transistors, demonstrating how digital computation can be constructed at the transistor level.

The adder takes two 2-bit binary inputs and produces:

- A Sum output

- A Carry output

The circuit runs on a 5V input, and due to the voltage drop across the transistor logic stages, the output logic-high measures approximately 2.2V. In this implementation:

2.2V ≈ logic “1”

0V or very low voltage ≈ logic “0”

During testing, I used two voltmeters to display the outputs in real time:

- The left meter shows the Carry bit

- The right meter shows the Sum bit
