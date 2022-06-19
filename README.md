# IVDC's Projects for IITISoC '22

We at the IVDC Club are elated to be part of IITISoC '22 for the first time ever! IITISoC is an excellent opportunity for the students of IIT Indore to enhance your skills and get started with Open-Source Contribution. We present to you projects in Autonomous Driving, Industry 4.0, Autonomous Underwater Vehicles (AUVs) and Unmanned Aerial Vehicles (UAVs).
## Autonomous Driving: Self-Driving Cars and ADAS


### 1. Autopilot system for _Tesla_ cars: BEGINNER
**Description**: While on the highway, the monotonous speed
control is a bit tiresome for drivers (especially for long
distances and longer durations). Lane Assist and Adaptive
Cruise Control (ACC) features can help the drivers in these
situations. Depending on the actions of other
objects/vehicles in the car's immediate vicinity, these
systems can slow down and stop the vehicle when required.

**Specifications**:
- Computer Vision Pipeline for Lane detection should be
efficient in detecting the free path on the road.
- Motion planning and control systems are needed to steer
the vehicle to have the least cross-track error and
automatic lane centering.
- Bonus points for an active obstacle avoidance system to
change lanes and avoid other cars in the lane.

### 2. Autonomous Valet Parking: INTERMEDIATE

**Description**: Autonomous valet parking requires the vehicle
to perceive, plan and execute the necessary motion to cars
in parking areas. The sensors on the vehicle provide the
vehicle with information about its current position and the
current conditions of its surrounding environment. Using
this information, vehicle control should be evaluated.

**Specifications**:
- The sensors present may be LiDAR, RGBD camera, and
ultrasonic sensors.
- The vehicle must be able to park under challenging
arrangements and even in cramped spaces, keeping in
mind the ease of moving out of the parking space.

### 3. AI4CARS: ML package for self-driving cars: ADVANCED
**Description**: Design a plug-and-play Computer Vision Package
in _Python_, implementing multiple applications for
self-driving cars.

**Specifications**:
Implement APIs that could achieve
- Object Detection (cars, bikes, pedestrians, traffic
lights, signs) for driving scenes.
- Lane finding
- Image Segmentation
- Object Tracking

## Smart Warehouse Transportation (Industry 4.0)

### 1. AGV - Autonomous Ground Vehicle: BEGINNER
**Description:** In most warehouses, AGVs are used for
transporting packages for different tasks (sorting,
packaging, labelling, etc.) in a warehouse. The task is to
design a grid-based system for handling pick-and-place tasks
that are an integral part of the in-warehouse shipping
system.

**Specifications**:
- The AGV can be an open-source model or custom-made with
the basic functionality of a warehouse AGV.
- A simulation of the warehouse demonstrating the task is
to be made.

### 2. AGV Manipulator Arm Coordination: INTERMEDIATE
**Description:** In warehouse conditions, only AGVs cannot cater
to all the material transport requirements. For some of the
unorthodox manoeuvres like barcode scanning and inventory
auditing, and packaging, Manipulator's arms are required.
These two systems (AGV and Manipulator Arm) must coordinate
well for a fully autonomous warehouse setup. Designing
robust, efficient, and fast algorithms is the key to solving
these problems.

**Specifications:**
- You are free to choose between _ROS1_ and _ROS2_ for this
task.
- Tasks should be demonstrated in a simple simulation
environment.

### 3. LiDAR Obstacle Avoidance Robots: ADVANCED
**Description:** Large Warehouses (such as those of Amazon) are
highly dynamic environments with many moving objects.
Autonomous Mobile Robots (AMRs) with 3D LiDARs and other
sensors are deployed to move goods around the warehouse for
efficient material movement in a robust and fast manner.
Since there are also people working around, these advanced
robots have to perceive the environment, make intelligent
decisions and make judgments of static and dynamic obstacles
(or other robots) around it to avoid collisions and hazards.
LiDAR-based obstacle avoidance and dynamic tracking systems
must be deployed with a robust decision-making architecture.

**Specifications:**
- Any 3D LiDAR may be used (_Ouster OS_ series or _Velodyne
Puck_).
- Assume the robots are slow-moving.
- A C++ based collision avoidance and planning module is
preferred for such high-speed and high-accuracy tasks.
- A few scenarios may be simulated with the developed
software stack.

## Autonomous Underwater Vehicles (AUV)

### 1. Autonomous Submarine Navigation: INTERMEDIATE
**Description:** Underwater Surveys are an important part of
data collection and research. Manual surveys have certain
limitations and some risks involved with them. This is where
an AUV can help obtain high-quality data without causing
much trouble, but navigating underwater can be highly
challenging.
The task is to develop an algorithm for navigating from a
specified start point to the endpoint, avoiding obstacles in
the path.

**Specifications:**
- The AUV would have cameras, depth sensors, DVL, 9DOF
IMU (AHRS), etc.
- The AUV must have an 8-thruster configuration.
- Use a suitable simulator for implementing and testing
your implementations.

## Unmanned Aerial Vehicles

### 1. Last-Mile Delivery Drones: INTERMEDIATE
**Description:** _TATA 1mg_ is a pharmaceutical company that
delivers medicines at the doorstep via their courier
executives. Delivery drones can achieve the same task with a
fraction of the cost, especially since the payload is
minimal. An optimised delivery system should be ideated for
a drone fleet to plan out the delivery providing the routing
and mission-path planning.

**Specifications:**
- The drone environment from the warehouse to the
doorstep will be simulated. There may be multiple
houses in a locality for which the trips need to be
planned.
- The simulation should also log major events with
individual timings so that the performance of the whole
process can be analysed.
- Brownie points: Solving the problem involving the
constraint of limited battery time of the drone.

### 2. Aerial Surveying in IIT Indore: INTERMEDIATE
**Description:** IIT Indore has a considerable land area under
thick forest cover. In the blazing hot summers of Indore (as
we all have experienced), there are chances of bushes
catching fire and escalating to a forest fire. To prevent
it, an aerial surveying drone equipped with infrared cameras
and other sensors can be used to predict the areas which are
potential hotspots.

**Specifications:**
- Recognize abnormally high-temperature spots of the
forest cover to detect and signal the ground station
immediately.
- Identify high-risk areas that generally have higher
temperatures than average.
- Bonus Points for generalising the approach for
detecting animals (such as wild boar herds and
leopards) on our campus.

### 3. Aerial Mapping and GIS: ADVANCED
**Description:** Mountain roads generally run across hills with
deep valleys on either side, and they are cramped so tightly
that it is challenging for more than one vehicle to pass
through them at a time. The road becomes almost invisible in
_Ladakh_ and near the _Indo-Sino border_ after a snowfall. As
_China_ poses an increasing threat to security, the Indian
army must be cautious and plan before moving. Also, the path
must be free of any army bases or other establishments
across the border. UAVs are used to ensure safe and clear
ways for the movement of military and border security
personnel.

**Specifications:**
- The challenge is to develop an Unmanned Aerial Vehicle
(UAV) capable of mapping mountainous terrain.
- The UAV can have a downward-facing RGBD camera (or even
LiDARs), 9DOF IMU sensor, and GPS.
- The task must be completed in simulation using _ROS_ and
_Gazebo_ with a flight controller (such as _Ardupilot_ or
_PX4_).
- Bonus points for applying the mapping technique to
guide military vehicles in fog and heavy snow.
