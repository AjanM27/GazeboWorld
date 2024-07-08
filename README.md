# Gazebo World

## Introduction
This project demonstrates the use of Gazebo Classic Simulator to simulate a world where two bots autonomously move towards any object using `libFollowerPlugin.so`. Additionally, it utilizes another custom plugin to print a welcome message. The simulation environment includes multiple models such as persons, robots, cans, boxes, etc., placed around a central building. The primary objective is to showcase real-time simulation and physics capabilities using Gazebo.

## Instructions to Run
To run this project, follow these steps:

1. **Install Gazebo Classic:**
   Make sure Gazebo Classic is installed on your system. You can download it from [Gazebo's official website](http://gazebosim.org/).

2. **Set Plugin Path:**
  <P></P> Set the default path for plugins to the build directory using the following command in your terminal:</P>
   export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:~/gazeboProject/build
   
   Replace `~/gazeboProject/build` with the actual path to your project's build directory.

4. **Run the Simulation:**
Launch the world using the following command in the same terminal:

This command starts the Gazebo simulator with the `myWorld` environment where your simulation will be executed.

---

### Additional Notes:
- Ensure all dependencies are installed and configured properly before running the simulation.
- Adjust paths and environment variables as per your specific setup.
- Experiment with different configurations and plugins to explore Gazebo's simulation capabilities further.

This README provides a basic overview and setup instructions for your Gazebo Classic Simulator project. Feel free to expand and customize it further based on additional features or specific requirements of your simulation environment.


