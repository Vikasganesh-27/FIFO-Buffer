# FIFO-Buffer
# FIFO Module - SystemVerilog Verification

This repository contains the implementation of a **First-In-First-Out (FIFO) module** along with its **SystemVerilog-based testbench** for verification. The project includes transaction generation, driver, monitor, scoreboard, and an environment for a complete verification process.

## Features
- Implements a synchronous FIFO with read and write operations.
- Includes a SystemVerilog testbench using OOP-based verification components.
- Utilizes mailboxes for communication between generator, driver, monitor, and scoreboard.
- Ensures correctness with a self-checking scoreboard.

## Testbench Components
The testbench follows an object-oriented approach and consists of the following components:
- **Transaction:** Defines randomized transactions.
- **Generator:** Produces random read/write transactions.
- **Driver:** Applies generated transactions to the FIFO DUT.
- **Monitor:** Observes DUT signals and sends them to the scoreboard.
- **Scoreboard:** Checks correctness of FIFO operations.
- **Environment:** Connects and runs all components together.

## Running the Simulation
To run the simulation, use a SystemVerilog simulator such as **Xilinx Vivado or EDA Playground**. 

## License
This project is licensed under the MIT License.

