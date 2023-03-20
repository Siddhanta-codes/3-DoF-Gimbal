# 3-DoF-Gimbal
The Gimbal system has been a sensation in our
present generation as it improves the stabilisation of handheld
footage. It uses sensors and motors to stabilize and support the
camera. Our project is about a 3-DOF self-stabilizing platform. It
is using PID and Kalman filter to obtain filtered values regarding
the position of the accelerometer/gyroscope (MPU6050) as
feedback which it then uses to remain in the calibrated position
despite a displacement. Servo motors have been programmed to
obey the microcontroller based on the feedback received from the
gyroscope.
