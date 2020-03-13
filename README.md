# Real-Time-position-Estimation-And-Socket-Communication-In-Python-Real-Time,Multithreading

 
 
   Real-time 2D position estimation of a robot with a fixed camera outside of the game field with python. At the same time, the estimated x,y coordinates of the robot is send via Socket communication to the Raspberry pi on the robot in real time. The robot uses this coordinates to extract the map of the enviroment. By using motion detection and edge detection algorithms, a python is written for our robot project to be used to estimate the 2D position of the robot on the field in real-time with maximum performance. At the beginning, to reach the goal,color detection and edge detection algorithms are used but the error was very high, then motion detection algorithm is decided to be used instead of color detection. The error is dropped to 5%. While 2D positions of the robot is created, the socket communication algorithm is used to sent the x,y coordinate data to the raspberry pi on the robot to extract a map in real time. The algorithm works fine in estimation position from 10m away. The extreme cases havent beed tested yet.Additionally, we adjusted the codes to be not to send coordinate data if there is no movement on the camera.
