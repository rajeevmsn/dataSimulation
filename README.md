Objective is to simulate watch data (accelerometer and gyroscope data) for various motion/activity such as walking, sitting, running etc.


For data simulation we need to define motion and activity profiles with height, 3d acceleration, frequency and step size.

Function for walking will be something like `y(t) = A H Sin(2πf t + Φ) + Noise` 

_A = Amplitude corresponding to step length 
H = height 
f= step frequency 
t = time 
Φ = phase shift