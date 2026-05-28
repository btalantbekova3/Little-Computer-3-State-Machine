# Little-Computer-3-State-Machine
This project simulates a simple LC-2 processor using a state machine approach. It models how instructions move through different stages of execution in a CPU.

## Features

* Implements LC-2 instruction cycle using a state machine
* Supports basic instruction fetch, decode, and execute stages
* Handles control signals for each state
* Simulates register and memory operations
* Step-by-step execution tracing

## Tech Stack

* C programming language
* Finite State Machine (FSM) design
* Computer architecture concepts

## How It Works

The processor is broken into states:

* Fetch: Read instruction from memory
* Decode: Interpret instruction
* Execute: Perform operation
* Write-back: Store result

## Files in this project

* fsm.sim – defines the finite state machine (controls the steps of the CPU)
* datapath.sim – shows how data moves between parts of the CPU
* latches.sim – stores temporary values during execution
* kmap.xlsx – Karnaugh map used to simplify logic expressions
* metadata.yml – configuration and project information

## What this project does
This project simulates how a basic CPU works step by step.

- How instructions move through different states
- How control signals are generated
- How data moves through registers and memory
- How each clock cycle updates the system
- The main idea is to break CPU work into simple steps and simulate them.


## How to run
Run the simulator like this:
- ./sim fsm.sim
- Or run with all files:
- sim fsm.sim datapath.sim latches.sim


## What I learned
How a CPU works internally
How a state machine controls execution
How datapaths move data step by step
How logic design is simplified using Karnaugh maps
How hardware behavior can be simulated in software

