ROS2 Dynamixel and Tactile Sensors Interface 

Description of repo and its purpose: 
This project aims to add a software interface to a custom end effector that will be used in an  HRI study that focuses on how people can differentiate between successful and unsuccessful grasps.
The custom end effector is mounted to a linear actuator and consists of two independently actuated fingers equipped with tactile sensors. Each finger utilizes a dynamixel servo motor and a Contactile tactile sensor. 
Our main objective for this project is to create a ROS2 interface that interacts with off-the-shelf hardware, namely the tactile sensors, dynamixel motors, and the linear actuator. 
The interface should enable end effector opening/closing features with varying dynamixel operating conditions; position mode, torque mode, and sensory input from tactile sensors.
The utility of ROS2 ensures data is being sent and recorded synchronously across all nodes while the end effector is grasping objects. 
