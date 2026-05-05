# eyrc_Drone_Project
A Krishi Drone project developed as part of the eYantra Robotics Competition held by IIT Bombay, which uses image processing to identify infected and healthy crops, autonomously navigates to affected areas, and performs targeted pesticide spraying, improving farming efficiency.
--------------------------------------------------------------
## 🏆 Overview

This project was developed as part of the eYantra Robotics Competition (eYRC) conducted by IIT Bombay.

Our team was selected among the Top 50 teams across India, through which we received an autonomous drone hardware kit.

We designed and implemented an autonomous drone system capable of performing tasks with minimal human intervention, focusing on smart agriculture applications.
## 🤖 About eYantra

eYantra is a robotics initiative by IIT Bombay that promotes learning through hands-on projects in embedded systems and robotics.

The competition involves:

Multi-stage evaluation
Simulation and hardware implementation
Real-world problem solving
### Theme: Krishi Drone (KD) – Smart & Sustainable Farming

This project focuses on improving sustainable agriculture using robotics and automation. It is designed for a controlled farming environment, where an autonomous Krishi Drone is used to monitor crop conditions and perform necessary actions without continuous human involvement.

Instead of using a camera mounted on the drone, the system utilizes an overhead camera setup that continuously observes the field. This camera acts as the main vision system, capturing images of crops for further processing.

Using image processing techniques, the system analyzes crop conditions to detect signs of infection such as discoloration or disease patterns. Once an affected area is identified, the system calculates its position and directs the drone to move to that specific location. The drone then performs targeted pesticide spraying, ensuring that only infected plants are treated.

This method reduces unnecessary chemical usage, protects healthy crops, and increases overall farming efficiency by applying a precise and controlled approach.

To develop this system, we integrated multiple technologies including ROS 2, Gazebo simulation, PID-based control systems for drone stability, and Git/GitHub for version control and collaboration.
## 🧠 Technologies Used
- ROS 2
- Gazebo Simulation
- Python
- Image Processing
- PID Control System
- Linux
- Embedded Systems

## 📸 Project Highlights

## 🎥 Simulation Demo (Gazebo)
This video demonstrates the simulation of our autonomous drone system in Gazebo. The core of this system is a PID controller implemented in Python, which dynamically adjusts the drone’s movement by controlling parameters such as thrust, throttle, yaw, and pitch. We defined specific target coordinates in the code, and the drone continuously adjusts its position to reach and stabilize at those points. This was one of the most challenging parts of the project, as achieving accurate behavior in simulation requires a deep understanding and fine-tuning of:

P (Proportional) – immediate response to error
I (Integral) – accumulated error correction
D (Derivative) – prediction and damping of motion
Tuning these parameters correctly was crucial to ensure that the drone behaved in a stable and controlled manner.

[[watch the video]: https://youtu.be/qx7hLjOTvYE

## 🎥 Top Camera View & Coordinate Processing
This video showcases the top camera (overhead) view of the simulation, which plays a crucial role in providing positional feedback to the drone.

To ensure safety during testing, we physically constrained the drone using strings. This was necessary because, at times, the drone could drift out of the camera frame or move unpredictably, increasing the risk of collisions and potential damage. The strings allowed us to maintain control over its motion while still observing its behavior.

The camera captures the environment from above, and based on this visual input, we extract the coordinates required for navigation. These coordinates are then used by our Python-based control system, which continuously updates the drone’s movement.

We recorded this output directly from the system screen while running the Python script, demonstrating how the drone responds in real time to the incoming coordinate data.

This highlights the integration between visual input and control logic, where the drone dynamically adjusts its position according to the processed coordinates.

[[Watch the video]: https://youtu.be/TyzEd0tCLXA

### 📌 This video demonstrates how the drone uses top-view camera input to determine coordinates and navigate while being safely constrained during testing.

## 📦 Hardware Kit Received
<img width="1600" height="892" alt="image" src="https://github.com/user-attachments/assets/d37b7184-1f25-408d-a4ce-2ce350852b49" />

## 🛠️ Setup & Development
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/92138870-7ace-467a-9258-9f6128425172" />

## Hardware Kit Photo
<img width="1280" height="775" alt="image" src="https://github.com/user-attachments/assets/5921f20f-4350-4e97-949a-0453d0f20164" />

## Work in progress
<img width="1130" height="708" alt="Screenshot 2026-05-05 212610" src="https://github.com/user-attachments/assets/997be78a-f495-4859-9fda-f1a22468a7b2" />




<img width="814" height="563" alt="setup" src="https://github.com/user-attachments/assets/829a604b-21c1-454e-8a7d-c9c74e5db7c5" />

## 🚀 Learning Outcomes
- Practical experience in autonomous systems
- Understanding of drone control and stability
- Exposure to real-world robotics challenges
- Strong teamwork and collaboration skills

## 📌 Conclusion

This project provided hands-on experience in building an autonomous drone system for agriculture, combining image processing, control systems, and robotics. It strengthened our ability to solve real-world engineering problems using technology.

## 📬 Connect
If you liked this project or want to collaborate, feel free to connect! [adityadengale23@gmail.com] 
### My teammates : 1. Ameya Degaonkar 2. Sarthak Benodkar 3. Pranav Rokade


