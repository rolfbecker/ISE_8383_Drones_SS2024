# ISE_8383_Drones_SS2024 - DRAFT! (under development)
Material for the Drone Technology elective module at HSRW. The curriculum is developed with the assistance of Copilot GPT-4.

**PROMPT #01:**


```
I would like to design an applied robotics course for ROS2 at a university.
It is for an electrical engineering program, 4. semester.
The students have no previous knowledge in robotics. The course comprises 12 meetings with 3 hours each.
The course should cover intoduction to ROS2 and simulation with Gazebo.
Furthermore the students have to assemble, program and use a physical 4 wheeled robot.
The robot is based on NVIDIA Jetson for computer vision and equipped with a lidar for SLAM.
Please suggest a curriculum.
```

Certainly! Designing an **applied robotics course for ROS2** tailored to electrical engineering students with no prior robotics knowledge is an exciting endeavor. Let's create a comprehensive curriculum that covers essential topics, hands-on experiences, and practical skills. Here's a suggested outline:

## **Applied Robotics Course for ROS2 Curriculum**

### **Week 1-2: Introduction to ROS2 Basics**
- **Objective**: Familiarize students with the Robot Operating System (ROS2) framework.
- **Topics**:
    - What is ROS2?
    - ROS2 architecture and communication model.
    - Setting up ROS2 environment on NVIDIA Jetson.
    - Basic ROS2 commands (e.g., `roscore`, `rosrun`, `roslaunch`).
    - Creating ROS2 workspaces and packages.
    - Hands-on: Writing a simple ROS2 publisher and subscriber.

### **Week 3-4: Gazebo Simulation with ROS2**
- **Objective**: Introduce students to Gazebo, a powerful robot simulation environment.
- **Topics**:
    - Overview of Gazebo and its integration with ROS2.
    - Creating and launching robot simulations in Gazebo.
    - Interacting with simulated robots using ROS2.
    - Basic Gazebo plugins (e.g., joint controllers, sensors).
    - Hands-on: Simulating a robot model in Gazebo.

### **Week 5-6: NVIDIA Jetson for Computer Vision**
- **Objective**: Understand the role of NVIDIA Jetson in robotics and computer vision.
- **Topics**:
    - Introduction to Jetson platforms (e.g., Jetson Nano, Jetson Xavier).
    - Installing JetPack SDK.
    - Setting up Jetson for ROS2 development.
    - Basics of computer vision libraries (OpenCV, CUDA).
    - Hands-on: Implementing basic computer vision tasks on Jetson.

### **Week 7-8: Lidar and SLAM**
- **Objective**: Explore Simultaneous Localization and Mapping (SLAM) techniques using Lidar.
- **Topics**:
    - Lidar principles and types.
    - ROS2 integration with Lidar sensors.
    - Implementing SLAM algorithms (e.g., Hector SLAM, Cartographer).
    - Mapping and localization using Lidar data.
    - Hands-on: Building a 2D map using Lidar data.

### **Week 9-10: Assembling and Programming the Physical Robot**
- **Objective**: Hands-on experience with hardware assembly and programming.
- **Topics**:
    - Selecting components (motors, wheels, chassis).
    - Wiring and connecting sensors (Lidar, IMU).
    - Assembling the 4WD robot.
    - Writing ROS2 nodes for robot control (e.g., motor control, Lidar data processing).
    - Hands-on: Programming the robot for basic navigation.

### **Week 11-12: Advanced Robot Applications**
- **Objective**: Apply learned concepts to real-world scenarios.
- **Topics**:
    - Object detection using computer vision.
    - Path planning and obstacle avoidance.
    - Autonomous navigation using ROS2 Navigation Stack.
    - Final project: Implementing a complete autonomous navigation system on the physical robot.

### **Assessment and Evaluation**
- Regular quizzes, assignments, and a final project demonstration.
- Encourage students to document their progress in ROS2 notebooks or reports.

Remember to adapt the pace and depth of each topic based on your students' learning curve. Provide ample hands-on practice and encourage creativity in their final projects. Happy teaching! 🤖📚

Quelle: Unterhaltung mit Bing, 03/02/2024
(1) Courses - ROS Wiki. http://wiki.ros.org/Courses.
(2) ROS2 Robotics Developer Course - Using ROS2 In Python | Udemy. https://www.udemy.com/course/ros2-robotics-developer-course-using-ros2-in-python/.
(3) ROS 2 Industrial Training — ROS-Industrial. https://rosindustrial.org/ros-2-industrial-training.
(4) Implementing Robotics Applications with ROS 2 and AI on the NVIDIA .... https://developer.nvidia.com/blog/implementing-robotics-applications-with-ros-2-and-ai-on-jetson-platform-2/.
(5) Getting Started with ROS 2 on Jetson AGX Orin™ - Stereolabs. https://www.stereolabs.com/blog/getting-started-with-ros2-on-jetson-agx-orin.
(6) GitHub - jetsonhacks/installROS2: Scripts to install ROS2 on the NVIDIA .... https://github.com/jetsonhacks/installROS2.
(7) Learning NVidia Isaac ROS2 — Part 1 — Dev Setup. https://robofoundry.medium.com/learning-nvidia-isaac-ros2-part-1-dev-setup-0e54a3325082.
(8) Accelerating AI Modules for ROS and ROS 2 on NVIDIA Jetson Platform. https://developer.nvidia.com/blog/accelerating-ai-modules-for-ros-and-ros-2-on-jetson/.
(9) undefined. https://index.ros.org/doc/ros2/Installation/Foxy/Linux-Development-Setup/.
