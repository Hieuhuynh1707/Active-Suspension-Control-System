```markdown
Active Suspension Control System

This project implements an active suspension control system using LQR controller, co-simulated in MATLAB/Simulink and CarSim.

1. Tools Used
- MATLAB/Simulink
- CarSim 2017.1
- Vehicle: D-Class SUV

2. Files
- `active_suspension_control_system.pdf` - Project report
- `Car_with_active_suspension_controller.slx` - Simulink model
- `video/Car_run_on_the_curve.mp4`, `video/Car_run_on_the_hump.mp4`, `video/Car_run_on_the_random_road.mp4`- Simulation demo video
- `*.par` - CarSim vehicle and road configuration

3. How It Works
The LQR controller reads suspension states from CarSim and sends control force back to the vehicle model in real time. The goal is to reduce body movement and improve ride comfort compared to a passive suspension system.

4. Results
The active suspension with LQR control shows better performance than passive suspension in terms of body acceleration and wheel displacement.
