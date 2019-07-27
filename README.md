# KalmanFilter-Vehicle-GNSS-INS
project is about the determination of the trajectory of a moving platform by using a Kalman filter. For this purpose a kinematic multi sensor system (MSS) is used, which is equipped with three fiber-optic gyroscopes and three servo accelerometers. Additionally, the MSS contains an accurate RTK-GNSS. The system is adapted to a trolley, which can be pushed by a human being, however, it is also possible to adapt the system to a car or another moving vehicle. During the exercise real measurements are recorded at the Campus Poppelsdorf (University of Bonn) with the system. The goal is to determine the trajectory of the trolley via Kalman filtering in 2D by using a simplified motion model (constant accelerations, constant angular rates, motion only possible along the x-axis of the body frame) as well as the observations of the IMU (i. e. accelerations and angular rates) and the GNSS receiver (2D positions).

<div align="center">
	<img src="/images/trolley.png" alt="trolley" width="400" title="nlos"/>
</div>