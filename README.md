# Walker-Project
Mechatronic Project at Helmholtz Institute for Biomedical Engineering:
Modeling, simulation and control of a motorized walker


First Step "Measuring phsyical quantities for modeling":
The mass of the walker including battery, motors and motor controllers 
and the moment of inertia around the walker's axis of rotation were measured. 

The moment of inertia of the brushless DC motors was estimated, 
since no information was provided by the manufacturer.

Second Step "Modeling and Simulation":
The principle of modeling is based on the inverse pendulum.
So we have derived the state-space representation of the walker, 
linearizing in the disered operation point. 
The dynamic of the motors was neglected.

Third Step "Designing the controller":
The state feedback gain was determined by using the infinite horizon LQR.


Used Software:
MATLAB/Simulink
dSPACE ControlDesk

Used Hardware:
dSPACE RTI MicroAutoBox
Inertial Measurement Unit
CAN Bus Shield
Arduino Nano
Battery
BLDC Motors
Motor Controller




https://user-images.githubusercontent.com/59392606/148139221-cd9ee1a1-c1e1-4755-bc11-36138f024e3a.mov


