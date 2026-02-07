# Robot-Assisted Biopsy Simulation Using a TX60 Robot

## General Description
This project consists of the simulation of a robot-assisted breast biopsy procedure using a TX60 industrial robot. The system reproduces the main stages of a core needle biopsy, including tool pickup, controlled needle insertion, and sample extraction.

The simulation is designed to analyze the application of robotic systems in minimally invasive medical procedures, with particular emphasis on precision, safety, and repeatability. The project aims to bridge the gap between industrial robotics and clinical workflows through a controlled simulation environment.

The project places special emphasis on:
- Robotic motion planning and trajectory definition
- Safety and speed control during medical procedures
- Manual supervision and human–robot interaction
- Analysis of simulated versus real clinical procedures

---

## Main Objectives
- Simulate a core needle breast biopsy procedure using an industrial robot
- Define robot trajectories, tool reference frames, and working points
- Implement speed control and safety constraints during critical motions
- Analyze differences between simulated and real biopsy procedures

---

## Materials and Setup
The simulation setup includes the following elements:

- **TX60 industrial robot**  
  Used to execute the biopsy simulation and perform controlled movements.

- **Syringe used as biopsy tool**  
  Simulates the biopsy needle during insertion and extraction.

- **Silicone breast models placed on cork blocks**  
  Represent the anatomical target for the biopsy procedure.

- **Modeling clay**  
  Used to stabilize the tool during the procedure.

All reference frames, tools, and robot positions were manually defined based on the physical configuration of the experimental setup.

---

## Procedure Overview
The system initializes at a predefined home position and displays a user-controlled menu to start or stop the procedure.

Once initiated:
- The robot performs a syringe pickup sequence
- Manual user confirmation is required to ensure correct tool grasping
- The biopsy procedure consists of three linear insertion movements at different extraction points
- Safety clearance motions are executed between each insertion to avoid collisions

After completing the biopsy sequence, the robot releases the tool and safely returns to the home position.

---

## Safety Considerations
Several safety measures were implemented to ensure reliable and controlled operation:

- Reduced robot velocity during needle insertion movements
- Manual confirmation of tool pickup
- Predefined safe positions to prevent collisions
- Continuous user supervision throughout the procedure

These measures help ensure safe interaction between the robot, the environment, and the simulated medical setup.

---

## Design and Architecture
The simulation follows a structured robotic workflow, with clearly defined phases for initialization, tool handling, biopsy execution, and shutdown.

Key design principles include:
- Precision and repeatability of robotic movements
- Clear separation between motion planning and user control
- Emphasis on safety-critical operations
- Reproducibility of the simulated medical procedure

This design allows the simulation to be easily extended or adapted for future studies involving robotic-assisted medical interventions.

---

## Authors
**Eva Matabosch**  
**Iman Tarfass**
