# simulating_container
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Case Study Specifications

Vessel Arrivals: Time between vessel arrivals follows an exponential distribution with an average of 5 hours.

Vessel Capacity: Each vessel carries 150 containers.

Berth Slots: The terminal has 2 berths.

Quay Cranes: There are 2 quay cranes, each capable of operating on any berth and lifting one container at a time. It takes 3 minutes to move one container.

Trucks: There are 3 trucks. It takes 6 minutes for a truck to drop off a container at the yard block and return.

Logging: A simple log should be maintained for each event, including the current simulation time.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Explanation

Terminal Class: Represents the terminal with resources for berths, cranes, and trucks.

Vessel Process: Simulates the vessel's journey through the terminal including arriving, waiting for a berth, unloading containers, and leaving.

Generate Vessels Process: Continuously generates vessels arriving at the terminal based on an exponential distribution.

Simulation Execution: Creates the simulation environment, initializes the terminal, and starts the vessel generation process.

The simulation runs for 24 hours (1440 minutes).

![image](https://github.com/user-attachments/assets/633bc1fb-831f-46b1-a29f-ef11e65821ff)
                                        
