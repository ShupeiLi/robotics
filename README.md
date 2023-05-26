# Instructions
Team: &lt; Pi team &gt; \
Siwen Tu, Lin He , Ruilin Ma, Chenyu Shi, Shupei Li\
Robotics, 2023 Spring, Leiden University

### Gesture control
#### Hardware environment
- Picar-4wd + RPi Camera v3 (wide)
- A computer with camera

#### Software environment
- picamera2
- opencv-python
- cvzone
- socket

#### Usage
1. Change the variable `host` (Line 5) in `hands_control_pc.py` to "your ip address". Open the port 6666.
2. Change the variable `host_ip` (Line 7) in `hands_control_car.py` to "your ip address".
3. Run `python3 hands_control_pc.py` on the computer.
4. Run `python3 hands_control_car.py` on the car.
5. Use gestures to control the car.

### Autonomous driving
