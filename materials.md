---
title: OER
---

# **Open Educational Resources (OER)**

## Materials Overview

This repository contains Open Educational Resources (OER) developed for semiconductor education at the high school (HS) and early undergraduate (CSUF) level.

The materials are designed using a **layered learning model**:
- **High school students** focus on conceptual understanding, systems thinking, and explanation
- **CSUF undergraduate students** engage in technical implementation, modeling, and tool-based workflows

The **same OER materials** are used across both groups, with different depth, tools, and deliverables. These materials are also used directly in a 9-week summer program, where they are piloted, refined, and validated.

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
│   ├── project_01_rf_signal_chain/
│   ├── project_02_rtl_controller/
│   ├── project_03_mixed_signal_verification/
│   ├── project_04_rtl_to_gds_mini_flow/
│   ├── project_05_manufacturing_and_test_dft/
│   └── project_06_packaging_and_signal_integrity/
│
└── ai_tutor/
    └── verilog_ai_tutor.md
````

**OER Repo**: [https://github.com/jfaller-csuf/csuf-ssp-oer](https://github.com/jfaller-csuf/csuf-ssp-oer)

---

## Lectures

### Module 01: What Is a Chip?

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `Conceptual`

**Learning Outcomes:**

* Explain what a computer chip is and what it does
* Identify everyday devices that contain chips
* Describe the role of rules and logic in chips
* Communicate technical ideas using simple language

---

### Module 02: Inputs, Outputs, and Logic

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `Logic`, `Foundations`

**Learning Outcomes:**

* Identify inputs and outputs in real systems
* Understand “if–then” decision rules
* Create basic flowcharts and logic diagrams
* Relate everyday decisions to digital logic

---

### Module 03: Chip Design and Manufacturing Flow

**Audience:** HS (conceptual), CSUF (technical)
**Tags:** `HS`, `CSUF`, `Manufacturing`, `ASIC Flow`

**Learning Outcomes:**

* Describe the major steps in the chip design flow
* Understand why each step exists
* Explain the difference between design, fabrication, and testing
* Recognize real-world constraints in chip manufacturing

---

### Module 04: Digital Logic and State Machines

**Audience:** HS (conceptual), CSUF (implementation)
**Tags:** `HS`, `CSUF`, `FSM`, `Digital Design`

**Learning Outcomes:**

* Understand what a finite state machine is
* Describe states, transitions, and conditions
* Create state diagrams for simple systems
* Connect logical behavior to hardware implementation

---

### Module 05: Semiconductors in the Real World

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `Industry`, `Careers`

**Learning Outcomes:**

* Identify applications of semiconductors in industry
* Understand the roles of different engineers
* Recognize how design decisions affect cost and performance
* Reflect on career pathways in semiconductors

---

## Labs

### Lab 01: Introduction to Verilog

**Audience:** CSUF (primary), HS (optional/advanced)
**Tags:** `CSUF`, `HS-Advanced`, `Verilog`, `Hands-On`

**Learning Outcomes:**

* Understand the structure of a Verilog module
* Write simple combinational logic
* Simulate basic Verilog designs
* Interpret simulation waveforms

---

### Lab 02: Combinational Logic

**Audience:** CSUF
**Tags:** `CSUF`, `Verilog`, `Logic`

**Learning Outcomes:**

* Implement logic using assign statements and always blocks
* Translate truth tables into Verilog
* Debug simple logic errors

---

### Lab 03: Sequential Logic and FSMs

**Audience:** CSUF
**Tags:** `CSUF`, `FSM`, `Sequential Logic`

**Learning Outcomes:**

* Design FSMs using Verilog
* Use clocks and resets correctly
* Simulate and verify state transitions

---

### Lab 04: Simulation and Debugging

**Audience:** CSUF
**Tags:** `CSUF`, `Verification`, `Debugging`

**Learning Outcomes:**

* Write basic testbenches
* Identify functional bugs using waveforms
* Develop systematic debugging strategies

---

### Lab 05: Introduction to Synthesis

**Audience:** CSUF
**Tags:** `CSUF`, `ASIC Flow`, `Synthesis`

**Learning Outcomes:**

* Understand what synthesis does
* Run a basic synthesis flow
* Interpret area and timing results
* Recognize tradeoffs between performance and complexity

---

## Projects

> **Note:** All projects are designed to support both HS and CSUF students using a layered approach.
> HS students focus on system understanding and explanation, while CSUF students focus on implementation, modeling, and analysis.

---

### Project 01: RF Signal Chain Block Design

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `RF`, `Systems`

**Learning Outcomes:**

* Understand RF signal chains and system-level design
* Identify the role of LNA, mixer, filter, and ADC blocks
* Analyze gain, noise, and bandwidth tradeoffs (conceptual or simulated)
* Read and interpret real-world datasheets

---

### Project 02: Digital Control Logic for an RF System

**Audience:** HS (conceptual), CSUF (implementation)
**Tags:** `HS`, `CSUF`, `RTL`, `FSM`

**Learning Outcomes:**

* Understand how digital logic controls system behavior
* Design and analyze finite state machines
* Implement and simulate RTL control logic (CSUF)
* Debug functional behavior using testbenches (CSUF)

---

### Project 03: Mixed-Signal Verification Project

**Audience:** HS (conceptual), CSUF (technical)
**Tags:** `HS`, `CSUF`, `Verification`, `Mixed-Signal`

**Learning Outcomes:**

* Understand the role of verification in chip design
* Distinguish between functional and performance verification
* Write verification plans and test cases
* Debug design failures through simulation

---

### Project 04: RTL to GDS Mini-Flow

**Audience:** HS (conceptual), CSUF (hands-on)
**Tags:** `HS`, `CSUF`, `ASIC Flow`, `Manufacturing`

**Learning Outcomes:**

* Describe the complete RTL-to-layout design flow
* Understand timing, area, and physical constraints
* Experience synthesis and basic physical design (CSUF)
* Explain how code becomes silicon

---

### Project 05: Manufacturing & Test Awareness (DFT)

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `DFT`, `Yield`

**Learning Outcomes:**

* Understand why chips require testing
* Learn basic design-for-test (DFT) concepts
* Explore manufacturing yield and defect mechanisms
* Analyze cost vs. complexity tradeoffs in test design

---

### Project 06: Packaging & Signal Integrity Case Study

**Audience:** HS, CSUF
**Tags:** `HS`, `CSUF`, `Packaging`, `Signal Integrity`

**Learning Outcomes:**

* Understand how IC packaging impacts performance
* Learn parasitic effects (R, L, C)
* Analyze signal integrity limitations
* Recognize real-world physical constraints in RF systems

---

## AI Tutor Support

**Audience:** CSUF
**Tags:** `CSUF`, `Verilog`, `AI Support`

The Verilog AI Tutor is integrated to support:

* Learning Verilog syntax and concepts
* Debugging RTL code
* Understanding simulation behavior and waveforms

The AI Tutor is intended as a **learning aid**, not a replacement for independent thinking or design work.

App: [https://verilog-ai-tutor.vercel.app](https://verilog-ai-tutor.vercel.app)
