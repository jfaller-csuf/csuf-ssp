---
title: OER
---

# **Open Educational Resources (OER)**

## Materials Overview

This repository contains Open Educational Resources (OER) developed for semiconductor education at the high school (HS) and early undergraduate (CSUF) level.

The materials follow a **layered learning model**:
- **High school students** focus on conceptual understanding, systems thinking, and explanation
- **CSUF undergraduate students** focus on implementation, modeling, and engineering tools

Both groups use the **same core materials**, but differ in depth, tools, and deliverables.

---

## Program Theme

**“How a Program Becomes Hardware”**

Students progress from:
- Understanding chips and logic
→ to designing systems
→ to building a simple processor in Verilog (CSUF)
→ to explaining system behavior (HS)

---

## Repository Structure

```text
/
├── lectures/
│   ├── module_01_what_is_a_chip/
│   ├── module_02_inputs_outputs_logic/
│   ├── module_03_chip_design_flow/
│   ├── module_04_digital_logic_fsm/
│   └── module_05_semiconductors_in_the_real_world/
│
├── labs/
│   ├── lab_01_intro_to_verilog/
│   ├── lab_02_combinational_logic/
│   ├── lab_03_sequential_logic_fsm/
│   ├── lab_04_simulation_and_debugging/
│   └── lab_05_intro_to_synthesis/
│
├── projects/
│   ├── project_01_program_execution/
│   ├── project_02_alu_design/
│   ├── project_03_control_fsm/
│   ├── project_04_processor_integration/
│   ├── project_05_testing_and_debugging/
│
└── ai_tutor/
    └── verilog_ai_tutor.md
````

---

## Lectures

### Module 01: What Is a Chip?

**Audience:** HS, CSUF
**Focus:** Conceptual

* What a chip is and what it does
* Everyday examples
* Inputs, outputs, and rules

---

### Module 02: Inputs, Outputs, and Logic

**Audience:** HS, CSUF
**Focus:** Foundations

* Inputs and outputs in systems
* “If–then” logic
* Flowcharts and logic diagrams

---

### Module 03: Chip Design and Manufacturing Flow

**Audience:** HS (conceptual), CSUF (technical)

* Design → fabrication → testing
* Why each step exists
* Real-world constraints

---

### Module 04: Digital Logic and State Machines

**Audience:** HS (conceptual), CSUF (implementation)

* State machines and transitions
* System behavior over time
* Connection to hardware

---

### Module 05: Semiconductors in the Real World

**Audience:** HS, CSUF

* Industry applications
* Engineering roles
* Career pathways

---

## Labs

### Lab 01: Introduction to Verilog

**Audience:** CSUF (primary), HS (optional)

* Verilog module structure
* Simple combinational logic
* Simulation basics

---

### Lab 02: Combinational Logic

**Audience:** CSUF

* Implement logic in Verilog
* Translate truth tables
* Debug basic errors

---

### Lab 03: Sequential Logic and FSMs

**Audience:** CSUF

* FSM design in Verilog
* Clocking and resets
* State transitions

---

### Lab 04: Simulation and Debugging

**Audience:** CSUF

* Testbenches
* Waveform analysis
* Debugging strategies

---

### Lab 05: Introduction to Synthesis

**Audience:** CSUF

* What synthesis does
* Area and timing
* Design tradeoffs

---

## Projects

All projects follow a **layered approach**:

* HS → system understanding and explanation
* CSUF → implementation and analysis

---

### Project 01: How a Program Runs on Hardware

**Audience:** HS, CSUF

* Instruction execution
* Program flow
* Registers and operations

---

### Project 02: ALU Design

**Audience:** HS (conceptual), CSUF (implementation)

* Arithmetic and logic operations
* ALU role in a processor
* Verilog implementation (CSUF)

---

### Project 03: Control Unit (FSM)

**Audience:** HS (conceptual), CSUF (implementation)

* Instruction sequencing
* FSM-based control
* RTL design and debugging

---

### Project 04: Processor Integration

**Audience:** HS (conceptual), CSUF (hands-on)

* Connect datapath + control
* Execute simple programs
* Understand full system flow

---

### Project 05: Testing and Debugging

**Audience:** HS, CSUF

* Test case design
* Identifying failures
* Verification strategies

---

## AI Tutor Support

**Audience:** CSUF

The Verilog AI Tutor supports:

* Learning syntax
* Debugging code
* Understanding simulations

This is a **support tool**, not a replacement for learning.

App: [https://verilog-ai-tutor.vercel.app](https://verilog-ai-tutor.vercel.app)
