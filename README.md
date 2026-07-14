# 🤖 Multi-Robot Coordination Simulator

A Python-based warehouse automation simulator that demonstrates multiple autonomous robots performing package pickup and delivery tasks with route planning, obstacle avoidance, visualization, animation, and mission reporting.

---

## 📌 Project Overview

This project simulates a warehouse environment where multiple autonomous robots work together to transport packages from pickup locations to assigned delivery points.

The simulator demonstrates key robotics concepts such as multi-agent coordination, task allocation, path planning, warehouse navigation, and mission reporting.

---

## 🚀 Features

- Multi-Robot Warehouse Simulation
- Three Autonomous Robots
- Task Allocation
- Package Pickup & Delivery
- Warehouse Shelf (Obstacle) Representation
- Planned Robot Routes
- Animated Robot Movement
- Professional Color Mapping
- Robot Labels
- Mission Statistics Dashboard
- JSON Report Export
- Mission Summary Text Report

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Matplotlib
- JSON
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure

```text
multi-robot-coordination-simulator/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── notebook/
│   └── Multi_Robot_Coordination.ipynb
│
├── outputs/
│   ├── warehouse_map.png
│   ├── multi_robot_report.json
│   └── mission_summary.txt
│
└── screenshots/
    ├── 01_warehouse_environment.png
    ├── 02_planned_routes.png
    ├── 03_robot_animation.png
    ├── 04_robot_labels.png
    ├── 05_professional_map.png
    ├── 06_console_report.png
    ├── 07_json_output.png
    └── 08_final_result.png
```

---

## ⚙ Workflow

```text
Create Warehouse
        │
        ▼
Add Shelves (Obstacles)
        │
        ▼
Place Robots
        │
        ▼
Place Packages
        │
        ▼
Assign Delivery Targets
        │
        ▼
Assign Tasks
        │
        ▼
Plan Robot Routes
        │
        ▼
Animate Robot Movement
        │
        ▼
Complete Deliveries
        │
        ▼
Generate Reports
```

---


## 📊 Sample Console Output

```text
==================================================
          MULTI-ROBOT MISSION REPORT
==================================================

Robots Active      : 3
Tasks Assigned     : 3
Tasks Completed    : 3
Collisions         : 0
Mission Status     : SUCCESS

==================================================
```

---

## 📄 Sample JSON Output

```json
{
    "robots": 3,
    "tasks_assigned": 3,
    "tasks_completed": 3,
    "collisions": 0,
    "status": "Mission Complete"
}
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/Harsha1501/multi-robot-coordination-simulator.git
```

Navigate to the project directory:

```bash
cd multi-robot-coordination-simulator
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebook/Multi_Robot_Coordination.ipynb
```

Run all cells to execute the simulation.

---

## 🎯 Learning Outcomes

This project demonstrates:

- Multi-Agent Robotics
- Warehouse Automation
- Task Allocation
- Path Planning
- Robot Coordination
- Obstacle Representation
- Robot Visualization
- Simulation Design
- Data Visualization
- JSON Report Generation

---

## 🚀 Future Improvements

- A* Path Planning
- Dynamic Task Allocation
- Collision Prediction
- Robot-to-Robot Communication
- Dynamic Obstacles
- Battery Monitoring
- Fleet Scheduling
- ROS 2 Integration
- Gazebo Simulation
- Real-Time Multi-Robot Control

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Harsha**

GitHub: https://github.com/Harsha1501