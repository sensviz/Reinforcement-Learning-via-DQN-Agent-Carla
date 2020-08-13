# Reinforcement-Learning-via-DQN-Agent-Carla
The primary purpose of CARLA is to support development, training, and validation of autonomous driving systems.
CARLA also provides open digital assets for buildings and vehicles which are easily accessible and free to use. This simulation platform supports flexible specification of sensor suites, environmental conditions, full control of all static and dynamic actors, maps generation and much more.
Here the idea of CARLA is to have the server and clients. This architecture (server/clients) allows us to course run both the server and client locally on the same machines, but we could also run the environment (server) on one machine and multiple clients on multiple other machines.
Using CARLA, we can get all in a single simulation platform;
- A car
- An environment to drive that car
- We get sensors to place on car
- Like LIDAR, cameras, accelerometers, and so on.
We can use both 0.9.6 on Linux and 0.9.5 on Windows.

#System Requirements
Carla works with python = 3.7
This Code uses tensorflow=1.15 & keras=2.2.4. If you use latest version of tensorflow and keras it wont work.

Install Tensorflow
'pip install tensorflow==1.15'

Install Keras
'pip install keras=2.2.4'

For model.py
- Carla (Version=0.9.5 Windows & Version=0.9.6 LINUX)
- random
- os
- cv2
- time
- math
- numpy
- sys
- tqdm

For drive.py
- keras
- glob 
- os
- sys
- random
- time
- numpy
- cv2
- math
- tensorflow
- threading
- tqdm

#Running The Code
For model.py
- 'python model.py'
For drive.py
- 'python drive.py modelname.model'
For more information == https://pythonprogramming.net/introduction-self-driving-autonomous-cars-carla-python/
