
# Auto-racing Reinforcement Learning Project
### This project is an implementation of reinforcement learning techniques for autonomous driving in a simulated racing environment.

### Project Overview
Imagine having a car that drives itself! Well, that's exactly what I accomplished through my project using reinforcement learning-based techniques. By employing the Python programming language and the OpenAI Gym interfaces, I was able to create a driving simulator to simulate real-world scenarios.

To automate driving decisions, I utilized Q-learning and Actor-Critic algorithms. These algorithms learn from experience and improve their decision-making abilities over time. I initially implemented the Q-learning algorithm, extensively training and testing it in the simulator. I worked to optimize the reward function and update Q-values, resulting in a significant improvement in the model's performance.

However, I didn't stop there. I also implemented the Actor-Critic algorithm, which optimizes both the policy and value function simultaneously. This algorithm proved particularly effective in finding better actions in continuous spaces and demonstrated higher stability compared to the Q-learning algorithm.

Overall, my project showcased the immense potential of reinforcement learning techniques and their application to autonomous driving. Who knows, maybe one day we'll all be able to sit back and relax while our cars do the driving for us!

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
