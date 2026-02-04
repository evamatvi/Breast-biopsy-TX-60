Robotics Project – Breast Biopsy

Robot-Assisted Biopsy Simulation Using a TX60 Robot

Project Description

This project consists of the simulation of a robot-assisted breast biopsy using a TX60 industrial robot. The system reproduces the main stages of a core needle biopsy procedure, including tool pickup, controlled needle insertion, and sample extraction. The simulation is designed to study the application of robotic systems in minimally invasive medical procedures, with a focus on precision, safety, and repeatability.

##Objectives

Simulate a core needle breast biopsy procedure using an industrial robot

Define robot trajectories, tool frames, and working points

Implement speed control and safety constraints

Analyze the differences between simulated and real clinical procedures

##Materials and Setup

TX60 industrial robot

Syringe used as biopsy tool

Silicone breast models placed on cork blocks

Modeling clay for tool stabilization

All reference frames, tools, and robot positions were manually defined based on the physical configuration of the setup.

##Procedure Overview

The system initializes at a predefined home position and presents a user-controlled menu to start or stop the procedure. Once initiated, the robot performs a syringe pickup sequence with manual confirmation to ensure correct grasping. The biopsy process consists of three linear insertion movements at different extraction points, with safety clearance motions between each insertion. After completing the procedure, the robot releases the tool and returns to the home position.

##Safety Considerations

-Reduced velocity during insertion movements

-Manual confirmation of tool pickup

-Predefined safe positions to avoid collisions

-Continuous user supervision

-Limitations

The simulation does not include tissue deformation, force feedback, patient movement, or real-time imaging guidance. Anatomical and lesion models are simplified and idealized.

##Autors
Eva Matabosch and Iman Tarfass

