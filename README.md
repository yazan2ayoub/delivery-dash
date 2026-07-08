# Delivery Dash | 2D Logistics Simulation

An isometric/top-down 2D driving and neighborhood package distribution arcade game built in Unity. This project explores real-time material pickup mechanics, inertia tracking matrices, and dynamic vector-terrain interaction filters.

---

## 🕹️ Core Gameplay Loop
Players pilot a logistics vehicle through a residential layout grid. The core objective requires navigating tight urban boundaries to collect localized package assets from distribution centers and deploy them securely into active customer target drop zones under strict time parameters.

---

## ⚡ Technical Engineering Features

* **Rigid Trigger Volume Pipelines:** Engineered custom conditional trigger zones managing multi-stage package states (Uncollected ➔ In-Transit ➔ Delivered) to handle precise drop-off evaluations without layout clip errors.
* **Obstacle Momentum Degradation Engine:** Implemented full structural 2D rigidbodies across static residential infrastructure (houses, fencing assets, and mailboxes). Collisions run real-time kinetic calculations to dynamically degrade vehicle velocity proportionally to impact angles.
* **Dynamic Mud Friction Dampening:** Configured coordinate-based terrain layer queries. Whenever the vehicle vector crosses custom muddy surface boundaries, a velocity script instantly dampens the maximum acceleration parameters to simulate high-traction drag forces.
* **Vector-Based Kinetic Boosters:** Programmed modular overlay nodes that execute temporary vector overrides, multiplying vehicle max speed profiles upon capturing neon acceleration pickups.

---

## 🛠️ Tech Stack & Architecture
* **Game Engine:** Unity 2D Engine
* **Scripting Architecture:** C# Programming (Modular Behavior Segregation)
* **Physics System:** Unity Rigidbody 2D & Collision Matrix Filters
* **Input Controller:** Unity Input Manager Map
