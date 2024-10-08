## NPR 21-bit Computer Design

The NPR 21-bit Computer is a specialized architecture featuring a 21-bit word size, segmented into a 4-bit opcode for operation specification, a 15-bit address for memory referencing, and a 2-bit field for versatile addressing modes. This design accommodates four distinct addressing modes, enabling operations like immediate, direct, indirect, and indexed addressing.

### Table of Contents

1. [Key Features](#key-features)
2. [Instruction Set Architecture](#instruction-set-architecture)
   - [Memory Reference Instructions (MRIs)](#memory-reference-instructions-mris)
   - [Register Reference Instructions (RRIs)](#register-reference-instructions-rris)
   - [Input-Output Instructions (IOIs)](#input-output-instructions-iois)
3. [Instruction Cycle](#instruction-cycle)
4. [Design of Individual Components](#design-of-individual-components)
5. [How to Use the NPR 21-bit Computer Design Repository](#how-to-use-the-npr-21-bit-computer-design-repository)
   - [Prerequisites](#prerequisites)
   - [Steps to Run the Design](#steps-to-run-the-design)
6. [Demo](#demo)
7. [Contributing](#contributing)
8. [Support](#support)
9. [Conclusion](#conclusion)

### Key Features

- 21-bit word size
- 4-bit opcode
- 15-bit address
- 2-bit addressing mode field
- 32,768 memory locations
- Essential registers: Program Counter, Instruction Register, Accumulator, Memory Address Register, Memory Buffer Register
- Instruction set including load, store, add, subtract, and more

### Instruction Set Architecture

The instruction set architecture of the NPR 21-bit Computer includes:

- **Memory Reference Instructions (MRIs)**: 15 instructions with immediate, direct, and indirect addressing modes
- **Register Reference Instructions (RRIs)**: 13 instructions for direct calculations and manipulations of data in registers
- **Input-Output Instructions (IOIs)**: 8 instructions for communication between the computer and external devices

### Instruction Cycle

The instruction cycle of the NPR 21-bit Computer consists of four main phases:

1. **Fetch**: The instruction is fetched from memory.
2. **Decode**: The opcode and addressing mode are decoded.
3. **Execute**: The specified operation is performed.
4. **Interrupt**: Handles interrupts if enabled.

### Design of Individual Components

The NPR 21-bit Computer incorporates various components, including:

- **Registers**: AR, PC, TR, SC, IR, AC, DR, OUTR
- **Flags**: IEN, FGO, FGI, R, E, S, I0, I1
- **Memory**: 32K memory locations
- **ALU**: Performs arithmetic and logical operations
- **Common Bus Control**: Manages data transfer between components

### How to Use the NPR 21-bit Computer Design Repository

To run the NPR 21-bit Computer design using Logisim, follow these steps:

#### Prerequisites

- **Logisim**: Ensure you have Logisim installed on your computer. You can download it from the official website or use a compatible version.
- **NPR 21-bit Computer Design Files**: Obtain the Logisim project files for the NPR 21-bit Computer design, which may be included in this repository or provided separately.

#### Steps to Run the Design

1. **Open Logisim**

   Launch the Logisim application on your computer.

2. **Load the Project**

   - Click on **File** in the menu bar.
   - Select **Open** and navigate to the directory where the NPR 21-bit Computer design files are located.
   - Open the main project file (with a `.circ` extension).

3. **Familiarize Yourself with the Design**

   Review the components of the NPR 21-bit Computer design within Logisim. Key components to look for include:

   - **Registers**: Such as the Program Counter (PC), Instruction Register (IR), and Accumulator (AC).
   - **ALU**: The Arithmetic Logic Unit for performing calculations.
   - **Memory**: The memory blocks where instructions and data are stored.
   - **Control Unit**: Manages the execution of instructions.

4. **Simulate the Circuit**

   - Click on the **Simulate** menu and select **Tick** to start the simulation.
   - You can also use the **Run** button to execute the program continuously.
   - Observe the behavior of the registers and ALU as instructions are executed.

5. **Input Instructions**

   - To test the functionality, you may need to input instructions into the memory. This can typically be done by clicking on the memory component and entering values directly.
   - Ensure that the instruction format adheres to the NPR 21-bit architecture, which consists of a 21-bit word with specific opcode and addressing mode bits.

6. **Debugging and Monitoring**

   - Utilize the **Probe** tool in Logisim to monitor the signals and outputs from various components.
   - Check the values in registers and memory to ensure that the instructions are being executed correctly.

7. **Stopping the Simulation**

   - To stop the simulation, click on the **Simulate** menu and select **Stop**.
   - You can then make any necessary changes to the circuit or the instructions before running the simulation again.

### Demo

For a visual demonstration of the NPR 21-bit Computer in action, watch the following video on YouTube: [NPR 21-bit Computer Design Simulation](https://youtu.be/67BX-ju7b2o)

<!-- <div align="center">
[![NPR 21-bit Computer Design Simulation](https://img.youtube.com/vi/67BX-ju7b2o/0.jpg)](https://youtu.be/67BX-ju7b2o)

</div> -->

### Contributing

If you wish to contribute to the NPR 21-bit Computer project, please fork the repository and submit a pull request with your changes. Ensure that your contributions adhere to the project's coding standards and include appropriate documentation.

### Support

For any questions or further information, feel free to reach out:

- **Name**: Prashant Manandhar
- **Email**: prashantmanandhar2002@gmail.com
- **GitHub**: [Eemayas](https://github.com/Eemayas)
- **Website**: [https://www.manandharprashant.com.np/](https://www.manandharprashant.com.np/)

### Conclusion

The NPR 21-bit Computer design showcases a comprehensive and advanced architectural framework, incorporating essential components and a diverse instruction set to enable efficient computation within its 32,768 memory locations. This project serves as a valuable resource for understanding the fundamental principles and design considerations of basic computer architectures.

---
