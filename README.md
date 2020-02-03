# Traffiti
A Smart Traffic Controller implementing Reinforcement Learning to reshape how urbanites move around!

Tech Stacks:
Python * Keras * Numpy * SUMO * TraCI

Inspiration
While driving on Sherbrooke Street, at the intersection, it came to mind that transportation in general could be improved by attacking traffic light management.

What
Traffiti controls the traffic lights intelligently by using data on the current traffic to determine which traffic light pattern is the most appropriate to reduce overall wait time for drivers.

How
use Keras with reinforcement learning on SUMO (Simulation of Urban Mobility), a traffic simulation software, to train the underlying algorithm that Traffiti is run on.

Challenges
The setup, learning the TraCI (Traffic Control Interface), which is the SUMO API, and familiarizing with reinforcement learning with Keras.

Accomplishments
Able to dig out a solution from a complex research paper "An Efficient Deep Reinforcement Learning Model for Urban Traffic Control" and tried some cool technologies! (https://arxiv.org/pdf/1808.01876.pdf)

What's next for Traffiti
- Implement Traffiti IRL using computer vision
- Develop more features like protected lights, pedestrians, multi-lanes
- Store vehicle data for future usage on insurance, statistics, etc.
