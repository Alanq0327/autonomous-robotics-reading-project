# autonomous-robotics-reading-project# 
Independent Reading Project: Learning-Based Perception, Planning, and Control for Autonomous Robotic Systems

This repository contains an independent reading report on learning-based autonomous robotic systems, with a focus on robot navigation, multi-robot coordination, active semantic mapping, open-world task planning, and imitation-based manipulation.

The purpose of this reading project is to connect my previous hands-on experience in embedded robotics, state estimation, sensor fusion, real-time control, and robot learning with broader research problems in autonomous robotic systems. The selected papers provide a coherent view of how robots can perceive, plan, coordinate, and act reliably in complex physical environments.

## Motivation

My background is in embedded robotics, robotic perception, state estimation, and learning-based decision-making for autonomous systems.

In the Fast Robots project at Cornell University, I worked with a small autonomous mobile robot using IMU and ToF sensing, Kalman-filter-based distance estimation, yaw estimation, PID control, mapping, localization, BLE-based logging, and autonomous maneuver execution. This project gave me practical experience with the full perception--estimation--control pipeline on a physical robot.

I also explored cooperative multi-agent decision-making in the Overcooked-AI environment, where embodied agents need to coordinate task allocation, navigation, object handling, and delivery under shared spatial constraints. In addition, my previous work includes visual perception with improved YOLOv11 object detection and multi-agent path planning and conflict resolution in automated storage and retrieval systems.

These experiences motivated me to study recent research on learning-based robot autonomy, especially how autonomous systems can integrate perception, planning, coordination, and real-world deployment.

## Selected Papers

| No. | Paper | Main Topic | Connection to My Background |
|---|---|---|---|
| 1 | *NeuPAN: Direct Point Robot Navigation With End-to-End Model-Based Learning* | Direct point-based robot navigation | Fast Robots, ToF/IMU sensing, control |
| 2 | *Distributed Multi-Robot Collision Avoidance via Deep Reinforcement Learning for Navigation in Complex Scenarios* | Decentralized multi-robot navigation | Overcooked-AI, AS/RS path planning |
| 3 | *Semantics-Aware Receding Horizon Planner for Object-Centric Active Mapping* | Semantic active mapping | Fast Robots mapping, YOLO perception |
| 4 | *Language-Augmented Symbolic Planner for Open-World Task Planning* | Open-world task planning | Overcooked-AI, embedded AI command system |
| 5 | *BiKC+: Bimanual Hierarchical Imitation With Keypose-Conditioned Coordination-Aware Consistency Policies* | Bimanual imitation learning | Robot Learning, embodied coordination |

## Reading Logic

The five papers are organized around a progressive view of autonomous robotics:

```text
Raw Perception
    → Navigation and Collision Avoidance
    → Active Semantic Mapping
    → Task-Level Planning
    → Coordinated Manipulation
