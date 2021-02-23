# Obstacle-avoider
This code works better with an IR sensor. An IR sensor usually consists of an IR emitter and a sensor which detects the reflected IR rays. The principle behind obstacle avoidance is that when an object is closer to the sensor, the rays reflect from the surface of the obstacle and the sensor detects this. After being detected, the obstacle can then be avoided.
In case of the two sensor obstacle avoider, if one of the sensors has a higher reading then the other, i.e. if the obstacle is on one side of the robot, or if the robot is going towards a corner, it can properly steer away from the obastacle. 
In the tinkercad link, PIR  sensor is used instead of IR sensor for convenience and for testing the circuit. PIR sensors are usually used for motion detection of living beings. When a warm body passes in the range of a PIR sensor, the sensor can detect it since it causes differential changes in the output signal.
The modified circuit can therefore be used to avoid living obstacles. The obstacle avoidance works on the principle described above.
Designed on tinkercad. 
