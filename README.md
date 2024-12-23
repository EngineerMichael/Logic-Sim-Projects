# Logic-Sim
Computer Architecture Simulation Projects
Containing ALU, Micro-Controllers, 8 bit Registry & Variations of Logic Circuits

Logic-Sim: Computer Architecture Simulation Projects



Overview



Logic-Sim is a comprehensive simulation tool designed to model and simulate computer architecture components, such as Arithmetic Logic Units (ALUs), microcontrollers, 8-bit registers, and various logic circuits. The tool is intended for educational purposes, offering a hands-on way to understand the inner workings of digital circuits, microcontrollers, and computational systems.



The simulation environment is highly customizable and allows users to design, test, and visualize various logic circuits, with an emphasis on learning and experimentation with computer architecture principles.



This project is distributed under the GNU General Public License v3.0.



Features

• Arithmetic Logic Unit (ALU) Simulation: Simulate various ALU operations such as addition, subtraction, AND, OR, and more.

• Microcontroller Emulation: Simulate the behavior of simple microcontrollers with integrated peripherals.

• 8-Bit Registers: Simulate 8-bit data registers and observe their interactions with other components in a system.

• Logic Circuit Variations: Construct and simulate a wide variety of logic circuits, including combinational and sequential logic elements.

• Customizable Architecture: Build custom systems and experiment with different configurations of components.

• Step-by-Step Simulation: Step through operations to better understand how data flows through a system.

• Visualization Tools: View circuit diagrams and monitor signal flow to debug and verify system behavior.



Installation



Prerequisites

• Ensure you have a working installation of Git, Python, and GNU Make (for building the project).

• You will also need GTK+3 for GUI support (if you plan to use the graphical user interface).



Clone the repository



git clone https://github.com/yourusername/Logic-Sim.git

cd Logic-Sim



Install dependencies

• For Python-based simulations:



pip install -r requirements.txt



• For C/C++-based simulations (if applicable):



make install



Build the project



make



Run the simulation tool

• To start the command-line interface (CLI) version:



python logic_sim.py



• Or to start the GUI version (if supported):



./logic_sim_gui



Usage

1. Creating and Simulating Circuits:

• Choose from predefined components or create your own custom components (e.g., ALUs, registers, logic gates).

• Connect components together and configure their behavior.

• Simulate the circuit and observe how data moves through the system.

2. ALU Operations:

• Choose an arithmetic or logic operation (e.g., addition, subtraction, AND, OR) and provide the inputs.

• Observe the output and debug or optimize your design.

3. Microcontroller Programming:

• Load a simple program into a microcontroller.

• Observe how the microcontroller executes instructions, interacts with registers, and triggers different system responses.

4. Register Simulation:

• Experiment with 8-bit registers and explore how data is written, read, and transferred between components.

5. Logic Circuit Variations:

• Use a library of basic logic gates (AND, OR, NOT, NAND, NOR, XOR, etc.) to construct complex combinational and sequential circuits.

• Use clock signals to observe the behavior of sequential circuits like flip-flops, counters, and memory units.

6. Debugging and Visualization:

• Utilize built-in debugging tools to step through your simulation, view signal traces, and identify issues in your circuit or design.

• Visualize the logic flow in a graphical interface, if available, to better understand the behavior of your system.



License



This project is licensed under the GNU General Public License v3.0. You can freely modify and redistribute the code, provided that any modifications are also shared under the same license.



Summary of the GNU GPL v3.0 License:

• You can use, modify, and distribute the software as long as you make the source code available to others.

• Any derivative works must also be licensed under the GPL v3.0.

• You cannot impose any additional restrictions on the rights granted by the license.



For more details, see the full GPLv3 License.



Contributing



We welcome contributions to improve the functionality, features, and performance of Logic-Sim. To contribute:

1. Fork the repository.

2. Create a new branch for your feature or fix.

3. Make your changes.

4. Ensure that the code passes all tests.

5. Submit a pull request with a detailed description of your changes.



Acknowledgements

• This project was inspired by educational tools designed to help students and engineers understand computer architecture and digital logic.

• Contributions are welcome from the community to extend the project with more complex components, improved user interfaces, and optimized algorithms.



Contact



If you have questions, need support, or want to discuss the project, feel free to open an issue on the GitHub repository.



End of ReadMe.


GNU General Public License v3.0 
