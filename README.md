# Nano Processor Design Competition

The project is divided into several components, each with its own VHDL design, simulation code, schematic diagrams, and timing diagrams. 

## sub-components

The project involves the development of various sub-components of the nano processor. Those sub-components are as follows:

1. **4-bit Add/Subtract unit**

2. **3-bit adder**

3. **3-bit Program Counter (PC)**

4. **k-way b-bit multiplexers**
   - 2-way 3-bit multiplexer
   - 8 to 1 multiplexer

5. **Register Bank**

6. **Program ROM**

7. **Instruction Decoder**


## Conclusion

This nano processor is the result of modular development, where individual components were designed separately and then integrated to form a complete processor. This modular approach allowed us to create solid and reliable components, making the overall processor robust.

Some key takeaways from our project include:

- The instruction decoder plays a crucial role in the processor as it decodes instructions, activates data buses, and directs relevant information to other components.

- The 4-bit add/subtract unit can be configured to implement division and multiplication as well.

- We used tri-state buffers for implementing multiplexers, which is more efficient than using basic logic gates.

- Care should be taken with overflow detection as the Carry_out of the Add/Sub unit may not always catch overflow in all scenarios.

- The nano processor is designed to execute mathematical operations in the range of -8 to +7, with values outside this range considered as overflow.

Overall, our project provides a foundation for further improvements by adding new components and enhancing existing ones.

For more details, check the individual sections in this repository. Feel free to explore the source code, simulations, diagrams, and other resources.


