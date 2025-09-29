# Far Planner Autonomous Navigation System

The **Far Planner** project is a comprehensive autonomous navigation framework designed to enable fast, assured, and reliable mobility in complex environments. It integrates mapping, exploration, planning, and system orchestration into a cohesive platform for research, simulation, and real-world deployment.

## Overview

Far Planner brings together multiple subsystems under a unified architecture to address the key challenges of autonomous exploration and navigation. The framework combines real-time perception, intelligent planning, and coordinated system management to ensure robust and scalable operation across diverse robotic platforms.

## Core Components

### 1. Autonomous Exploration Framework

* Provides mapping, terrain analysis, and exploration strategies
* Integrates LiDAR-based odometry and local planning modules
* Includes tools for sensor simulation and 3D visualization

### 2. FAR Planner

* Implements the **Fast and Assured Reachability (FAR)** planning algorithm
* Handles boundary conditions, graph-based decoding, and visibility graph construction
* Offers RViz integration for goal setting and teleoperation support

### 3. Pipeline Orchestration

* Coordinates the execution of mapping, simulation, and planning subsystems
* Manages system timing and inter-component dependencies
* Provides a unified interface for launching the complete navigation pipeline

## System Flow

The platform operates as a synchronized pipeline:

1. Real-time mapping establishes an accurate environment model
2. Vehicle simulation or real robot control initializes the operating context
3. FAR Planner computes and refines navigation strategies for assured mobility

This layered sequence ensures each component is properly initialized and information flows seamlessly through the system.

## Key Features

* **Real-time operation** with LiDAR-inertial odometry and sensor fusion
* **Assured reachability** planning for safety and robustness
* **Modular workspaces** for exploration, planning, and orchestration
* **Visualization tools** for debugging, monitoring, and operator interaction
* **Extensible architecture** suitable for both research and deployment

## Applications

* Autonomous exploration of unknown terrains
* Simulation-based testing of navigation strategies
* Deployment on mobile robots requiring safe and efficient path planning
* Research in advanced robotics, mapping, and decision-making systems
