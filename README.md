# Control System Design for a Line-Following Robot

Control Systems – Practical Assignment  
University of Pretoria  
Completed: October 2021

---

## Project Overview

This project focuses on the modelling, design, and simulation of control subsystems used in a **line-following robotic platform**.

The system is divided into three main subsystems:

- Motor control subsystem
- Line-sensor subsystem
- State-control subsystem

Each subsystem was designed, simulated, and analysed to understand its behaviour within the overall control system. Transfer functions and linearised models were developed to describe system dynamics and evaluate performance.

👉 **[View Full Project Report (PDF)](docs/EBB320_Practical_Assignment_2.pdf)**

---

## Objectives

- Design and analyse the control architecture of a **line-following robotic system**
- Model the behaviour of multiple subsystems including:
  - motor subsystem
  - line-sensor subsystem
  - state-control subsystem
- Develop **functional block diagrams** representing the system structure
- Derive **transfer functions** describing system dynamics
- Create a **linearised model** for system analysis
- Simulate subsystem behaviour and evaluate system performance
- Implement control logic using embedded software

---

## Methodology

The system was decomposed into independent subsystems which were designed and analysed individually before being integrated into the complete control model.

### Motor Subsystem

The motor subsystem controls the movement of the robot and incorporates:

- DC motor control
- encoder feedback for rotational measurement
- power electronics for motor driving

Simulation models were created to evaluate motor behaviour and control response.

### Line Sensor Subsystem

The line-sensor subsystem detects the robot’s position relative to the track using optical sensors.

The subsystem converts sensor readings into signals that inform the control system about the robot's position relative to the line.

### State-Control Subsystem

The state-control subsystem determines the robot's behaviour based on sensor inputs.

This subsystem processes sensor signals and generates control actions for the motors, allowing the robot to maintain alignment with the line.

### System Modelling

The following modelling techniques were applied:

- functional block diagram modelling
- transfer function derivation
- linearisation of nonlinear system behaviour
- simulation of subsystem responses

---

## Experiments

Subsystem simulations were performed to analyse system performance and behaviour under different operating conditions.

The analysis included:

- motor subsystem simulations
- line-sensor subsystem simulations
- state-control subsystem simulations

Simulation results were evaluated to verify the correctness of the control design and to observe system dynamics.

---

## Tools & Technologies

- Control systems modelling
- Transfer function analysis
- Linearised system modelling
- Embedded programming
- **Arduino**
- **Python**
- DC motor control systems
- Optical line sensors
- Encoder feedback systems

---

## Notes

This repository contains the original academic report submitted for the course.

👉 **The full implementation code is included in the appendix section of the report.**
