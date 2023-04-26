
# Auto-racing Reinforcement Learning Project
### This project is an implementation of reinforcement learning techniques for autonomous driving in a simulated racing environment. Specifically, we use the DeepRacer environment and car model provided by Amazon Web Services (AWS).

### Project Overview
The project consists of two main components: the environment and the agent. The environment is responsible for simulating the racing track and providing the agent with relevant information such as the car's position, velocity, and sensor readings. The agent is responsible for making decisions about the car's actions based on this information and updating its policy accordingly to maximize its reward.

The project is implemented in a Jupyter Notebook using Python and the following libraries:

AWS RoboMaker Simulation Toolkit (RMS)
+ OpenAI Gym
+ Stable Baselines
+ TensorFlow
+ Project Structure
The repository contains the following files:

RLass2&3.ipynb: The Jupyter Notebook containing the project code.
model/: Directory containing the saved RL model.
logs/: Directory containing the logs generated during training.
README.md: This file.
### Getting Started
To run the project, you will need to follow these steps:

Install the required libraries: RMS, OpenAI Gym, Stable Baselines, and TensorFlow.
Clone the repository to your local machine.
Open the RLass2&3.ipynb file in Jupyter Notebook.
Follow the instructions in the notebook to train the agent and evaluate its performance.
Acknowledgments
This project is inspired by the AWS DeepRacer Scholarship Challenge. The implementation of the project is based on the tutorials provided by AWS and OpenAI.
