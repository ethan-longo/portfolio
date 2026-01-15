---
layout: default
title: Portfolio
---


Ethan Longo - Portfolio

# Backyard Sauna

## Overview

This project involved the full design and construction of a custom backyard sauna, from early concept development through detailed design, material selection, and hands-on construction.

## My Role

I was responsible for the entire design of the sauna, from dimensional planning, performance considerations, and researching best practices for DIY sauna construction. The project required balancing thermal efficiency, structural integrity, and aesthetics.

## Design Constraints & Requirements

Several constraints strongly influenced the final design:

- **Footprint limitation:** The concrete pad was limited to 12' x 8', which was the maximum allowable size without requiring a concrete permit (>100 square ft).
- **Height restriction:** Maximum height of 9 feet, due to the need to tie into adjacent roofline for visual aesthetics.
- **Functional layout:** Inclusion of both a sauna room and a change room.

## Design and Engineering Process

I began by creating 2D preliminary layouts in AutoCAD, followed by detailed 3D modeling in SolidWorks to validate proportions, clearances, and roof geometry. Multiple layout iterations were created and voted upon before settling on a two-room configuration:

- 6' x 8' change room
- 6' x 8' sauna room

The roof was designed with a single large slope, ranging from a height of 7 feet on the sauna end to a height of 9 feet on the changing room end. This sloped roof served 2 purposes:

- It reduced the sauna's internal volume, improving heating efficiency and cost.
- It allowed a clean visual connection to the adjacent roof.

I used Excel to calculate internal volumes, compare heating efficiency tradeoffs, and validate dimensional choices during the design phase.

## Skills & Tools

SolidWorks, AutoCad, Excel, Project design and planning, Hands-on construction, DIY research

## Outcome

I spent lots of time researching DIY saunas and what materials to use, construction techniques, and products to purchase. Cedar was the best wood to use for the interior walls of the sauna room due to its thermal stability, moisture resistance, and suitability for high-temperature environments. The complete sauna met all the initial requirements and resulted in a relaxing and stress-relieving environment.


# Tennis Training Robot

## Overview

Designed and built a prototype robot to act as an affordable alternative to tennis ball machines and coaches. The robot collects Tetrix balls, drives to a set court position, and launches them at random angles for customizable user training sessions.

## My Role

- Co-designed and assembled the mechanical systems, including conveyor belt intake, flywheel launcher, and drivetrain.
- Programmed software functions for ball intake, navigation, randomized shooting, and user input handling.
- Integrated sensors (colour sensor, gyro) for accurate ball detection and positioning.
- Contributed to project planning, troubleshooting, and testing.

## Key Features

- **Mechanical Design:** Conveyor belt intake, dual flywheel launcher with 2-level gear system (1300 rpm), and drivetrain for navigation.
- **Software:** Many different RobotC functions to navigate robot, perform the intake sequence, and shoot the Tetrix balls with randomized angles.
- **Inputs:** Colour sensor for ball detection, gyro for precise rotations, and user input for rounds and ball height.
- **Testing & Iteration:** Addressed drift and conveyor jamming by adjusting drive speeds, adding tray modifications, and upgrading motor power.

## Skills & Tools

LEGO EV3 Mindstorms, RobotC programming, Mechanical prototyping, Testing & debugging, Team collaboration, Project planning

## Outcome

Delivered a functional prototype robot capable of automated multi-round training with randomized ball launches. While some constraints limited full autonomy, the project demonstrated strong potential as a customizable, low-cost tennis training aid.

# Human Scooter System Modelling

## Overview

This project focused on modelling and analyzing a two-wheeled human transporter system, comparable to an inverted pendulum. Using MATLAB, Simulink, and SimulationX, the system was simulated to maximize upright travel distance without a controller. The project derived equations of motion, linearized the model, and implemented 3D simulations to evaluate balance and dynamics.

## My Role

- Collaborated on deriving equations of motion and linearizing the system model.
- Developed Simulink and SimulationX models for analyzing balance and stability.
- Designed and parameterized 3D models of the transporter and user.
- Conducted experiments with varying thrust forces and angles to optimize stability and distance.
- Contributed to analysis, results interpretation, and report writing.

## Key Features

- **System Dynamics:** Derived nonlinear and linearized equations of motion for wheel-base and user-pendulum subsystems.
- **Modelling Tools:** Implemented MATLAB/Simulink state-variable models and SimulationX 3D models.
- **Optimization:** Tuned thrust force and initial angles to achieve maximum travel distance before tipping.
- **Results:** Achieved up to 16.5 meters of stable forward motion without a controller.

## Skills & Tools

MATLAB, Simulink, SimulationX, System dynamics modelling, Linearization, 3D simulation, Experimental analysis, Technical reporting

## Outcome

Delivered a validated system model of a two-wheeled transporter that demonstrated the importance of control systems for stability. While the open-loop system naturally tipped over, optimization experiments provided valuable insights into balance dynamics. This work laid the groundwork for future implementation of feedback control systems.

# Beam Balancer

## Overview

This project involved the design and construction of a tabletop robotic system capable of balancing a ping-pong ball along a beam using vision-based feedback and closed-loop control. The robot was developed as a team project with strict size constraints and required the integration of mechanical design, kinematic analysis, computer vision, and PID control to achieve stable and responsive ball positioning.

## My Role

- Designed the structural frame and linkage system in SolidWorks within strict volume constraints.
- Derived kinematic relationships relating the servo motor angle to the angle of the beam for control.
- Implemented computer vision using HSV colour thresholding and shape detection to track ping pong ball position along the beam.
- Tuned PID control gains to minimize overshoot and achieve fast, stable convergence to the beam center.
- Contributed to designing, assembly, and system testing.

## Design Constraints & Requirements

Several constraints strongly influenced the final design:

- **Size limitation:** Entire system constrained to a maximum volume of 200 mm × 190 mm × 90 mm so it could be within range of the camera.
- **Actuation:** Single servo motor permitted for beam control.
- **Stability:** Beam required a central pivot to allow symmetric balancing behavior.
- **Manufacturability:** Components limited to 3D printing and laser-cut acrylic, assembled using mechanical fasteners and bearings.

## Design and Engineering Process

The mechanical system was fully designed in SolidWorks, consisting of a central beam pivoted about a pin and actuated via a two-bar linkage driven by a single servo motor. The linkage geometry was selected to maximize angular resolution while remaining within the height constraint.

Kinematic equations were derived to relate the servo motor angle to the resulting beam angle, enabling accurate feedforward control and simplifying controller implementation. The beam pivot location was chosen to ensure symmetric response and stable balancing behavior.

For sensing, a camera-based vision system was used to detect the ping-pong ball's position along the beam. HSV colour thresholding and shape detection algorithms were implemented to robustly identify the ball under varying lighting conditions.

A PID controller was implemented to regulate ball position. Controller gains were tuned experimentally to reduce oscillations, minimize overshoot, and allow the ball to settle at the beam center in a short time. Iterative testing was used to refine both mechanical alignment and control performance.

Acrylic components were laser cut for structural elements, while custom mounts and brackets were 3D printed. All components were assembled using fasteners and bearings to allow rapid iteration and adjustment.

## Skills & Tools

SolidWorks, Mechanical Design, Kinematic analysis, PID control, Computer vision, 3D printing, Laser cutting, System integration,
