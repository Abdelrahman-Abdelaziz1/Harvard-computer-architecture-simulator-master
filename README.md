# 🖥️ Harvard Architecture Simulator (Java)

  📌 Overview

This project is a Java-based simulation of the Harvard Computer Architecture, designed to model how a processor interacts with separate instruction and data memories. 
The simulator demonstrates core computer architecture concepts including instruction parsing, memory management, and CPU execution cycles.

  🧠 Key Concepts

* Harvard Architecture (separate instruction & data memory)
* Instruction execution cycle (Fetch → Decode → Execute)
* Register-based processing
* Assembly-like instruction parsing

  🚀 Features

* 🧾 Instruction parsing from input files
* 🧠 Simulated CPU execution cycle
* 💾 Separate Instruction and Data Memory modules
* 🧮 Register management system
* 🔄 Step-by-step instruction execution
* ⚙️ Modular and extensible architecture

  🏗️ System Architecture

 # 🔹 Processor Module

*  CPU.java  – Handles instruction execution cycle and core logic

 # 🔹 Memory Module

*  DataMemory.java  – Stores and manages data
*  InstructionMemory.java  – Stores program instructions
*  Registers.java  – Manages CPU registers

 # 🔹 Instruction Handling

*  Instruction.java  – Defines instruction structure
*  Parser.java  – Parses instructions from input file ( instructions.txt )

 # 🔹 Input

*  instructions.txt  – Contains assembly-like instructions to be executed

  🔄 Execution Flow

1. Load instructions from file
2. Parse instructions into executable format
3. Fetch instruction from instruction memory
4. Decode instruction
5. Execute operation using CPU and registers
6. Update data memory if needed

  🛠️ Tech Stack

*  Language:  Java
*  Concepts Applied: 

  * Object-Oriented Programming (OOP)
  * Computer Architecture Simulation
  * Parsing & Interpretation
  * Memory Management

  🎯 Learning Outcomes

* Implemented a simplified CPU simulator
* Applied theoretical concepts of Harvard Architecture
* Built modular components for memory, processor, and parsing
* Simulated low-level instruction execution in a high-level language

  📚 Use Case

This project is intended for educational purposes to help understand how processors execute instructions and interact with memory in a Harvard Architecture system.

  👨‍💻 Author

Abdelrahman Abdelaziz
Data Science MSc Student | Software Engineering Enthusiast

