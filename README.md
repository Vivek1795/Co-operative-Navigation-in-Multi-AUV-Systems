# Co-operative-Navigation-in-Multi-AUV-Systems
Simulated multi-AUV system for underwater navigation using LiDAR, IMU, and flocking algorithms. Features coordinated tracking, obstacle avoidance, and dynamic group formation in GPS-denied environments. Includes AUV modeling, control, and blimp-based hardware prototype.

### Simulating Flocking and Obstacle Avoidance with Minimal Sensor Input in Underwater Environments

![Project Status](https://img.shields.io/badge/status-Prototype%20Complete-blue)
![Repo Size](https://img.shields.io/github/repo-size/your-username/multi-auv-flocking)

[🎥 Simulation Demo](https://youtu.be/16jqQIGX92Q) |

---

## 🧭 Project Overview

This project models cooperative navigation and behaviour in **multi-AUV (Autonomous Underwater Vehicle)** systems with limited sensor data. Inspired by the challenges of deep-sea environments—no GPS and minimal vision—we simulate group navigation using LiDAR, IMU, and a custom **flocking algorithm**. The system enables AUVs to follow a leader (the "lighthouse") and self-organize when nearby.

The prototype includes:
- A full simulation of AUV and follower robots using MATLAB & Simulink
- Real-time object detection and tracking
- A hardware demo using a blimp model as a proxy for the underwater AUV

---

## 🛠️ Core Features

- 🔄 **Leader-Follower Dynamics**: AUV acts as a lighthouse, other robots follow when within LiDAR range
- 📡 **Limited Sensor Simulation**: No GPS or vision—only LiDAR and IMU for tracking
- 🧠 **Flocking Behavior**: Decentralized grouping based on real-time detection
- 🏁 **PID-Controlled AUV**: Simulated thrust, drag, and lift in 6 DOF motion
- 💡 **Blimp-Based Hardware AUV**: A real-world prototype mimicking buoyant, stable motion

---

## 🧪 System Components

### 🔧 Simulation Modules
- **AUV Motion Model**: PID-controlled trajectory with hydrodynamic effects
- **Obstacle Detection**: LiDAR-based detection with a 90° field of view
- **Multi-Robot Coordination**: Discrete-time updates for real-time flocking logic
- **Grouping Algorithm**: Dynamic clustering of robots using potential fields

### 🤖 Hardware Prototype
- Simulated AUV implemented as a **stable-flying blimp**
- Adjusted thrust model using fewer motors (3 instead of 5)
- Demonstrates basic navigation and hold-level flight

---

## 📊 Visualizations

| AUV Path Tracking | Robot Flocking |
|-------------------|----------------|
| ![2D Trajectories](./images/auv-path.png) | ![Robot Grouping](./images/flocking.png) |

---

## 🧩 Tools & Technologies

- `MATLAB/Simulink` – Simulation of dynamics, PID control, sensor models
- `Mobile Robotics Toolbox` – Object tracking & lidar simulation
- `Python` (optional) – Control logic prototyping
- `Physical Blimp Prototype` – Real-world modelling of AUV buoyancy

---

## 🎯 Skills Demonstrated

- System Modeling and Simulation  
- Autonomous Robotics  
- Real-Time Object Tracking  
- Multi-Agent Coordination Algorithms  
- Hardware Prototyping and Integration  
- Applied Control Systems (PID, transfer functions)

---

## 📈 Results

- AUV successfully tracked in a simulated 3D underwater space  
- Follower robots efficiently converged into cohesive groups  
- Obstacle avoidance worked even under sensing constraints  
- Blimp-based AUV hardware verified lift-stability and path control  
- Validated thrust, drag, and lift forces with Simulink modelling

---

## 🔮 Future Scope

- 🌐 Integrate CAD models for accurate digital twins  
- 🌊 Apply environmental dynamics to all follower robots, not just the leader  
- ⚡ Upgrade AUV hardware to include IMU and multi-directional thrust  
- 🧠 Introduce Reinforcement Learning for adaptive flocking

---

## 📽️ Project Videos

- 📹 [Simulation Demo](https://youtu.be/16jqQIGX92Q)  

---

## 👨‍💻 Contributors

- **Vivek Sunil Kulkarni**
- Niyati Vaidya  
- Prajjwal Dutta  

> Arizona State University – Robotics Systems Design

---

## 📚 References

Full references can be found in the [📄 Project Report](./Project_Report.pdf)

---