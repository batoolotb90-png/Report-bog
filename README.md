Mechanical Design of a Simple Quadruped Robot Dog
1. Introduction

The objective of this project is to develop a preliminary mechanical design for a simple quadruped robot dog. The project focuses on understanding the basic mechanical concepts required to design a robot capable of standing and walking.

The study includes the robot body structure, leg design, degrees of freedom, motor selection, joint torque calculation, center of gravity and stability analysis, walking method, and expected mechanical problems.

The designed robot is based on a four-legged structure similar to a robotic dog, providing better stability and movement capability.

2. Body Shape and Mechanical Structure Design

The robot consists of a central body structure connected to four mechanical legs. The body is designed with a simple rectangular shape to support the motors and mechanical components.

The main dimensions of the robot model are:

Parameter	Value
Overall Length	199.3 mm
Overall Width	118 mm
Overall Height	98.3 mm

The main components of the structure are:

Central robot body.
Four mechanical legs.
Rotational joints.
Motor mounting locations.

The design provides a lightweight structure suitable for small robotic applications.

3. Leg Design

The robot uses four legs to achieve stability and imitate the movement of a real dog.

Each leg consists of:

Upper link connected to the robot body.
Lower link responsible for movement.
Rotational joints that allow movement.

The four-leg configuration increases the support area and improves balance during standing and walking.

Advantages of the leg design:
Better weight distribution.
Increased stability.
Ability to perform basic walking movements.
Simple mechanical construction.
4. Number of Joints and Degrees of Freedom (DOF)

The robot contains four legs, and each leg contains two main rotational joints.

The calculation is:

Number of legs = 4

Number of joints per leg = 2

Therefore:

DOF=4×2=8

The total degrees of freedom:

DOF = 8

The eight degrees of freedom allow the robot to control leg movements and maintain balance while walking.

5. Motor Selection

Because of the small size and lightweight structure of the robot, servo motors are selected for joint movement.

The recommended motor specifications are:

Parameter	Specification
Motor Type	Metal Gear Servo Motor
Required Torque	15–25 kg.cm
Operating Voltage	5–6 V
Number of Motors	8 Motors

Servo motors are selected because they provide:

Accurate position control.
Suitable torque for leg movement.
Easy control using microcontrollers such as Arduino.
6. Joint Torque Calculation

The required torque for a joint can be calculated using:

τ=F×L

Where:

τ = Joint torque (N.m)
F = Force caused by the load (N)
L = Distance from joint to center of mass (m)

Assumptions:

Mass acting on the joint:

m=0.5kg

The force is:

F=m×g
F=0.5×9.81
F=4.905N

The distance from the joint:

L=0.05m

Therefore:

τ=4.905×0.05
τ=0.245N.m

Converting into kg.cm:

0.245×10.2=2.5kg.cm

The theoretical required torque is approximately:

2.5 kg.cm

However, to ensure safe operation and overcome additional loads, a higher torque servo motor is selected:

15–25 kg.cm Servo Motor

7. Stability and Center of Gravity

The stability of the robot depends on the position of the center of gravity.

The center of gravity should be located near the center of the robot body between the four legs.

The design improves stability by:

Distributing the weight equally among four legs.
Keeping heavy components such as the battery near the center.
Maintaining the projection of the center of gravity inside the support area.

A larger support area results in better stability during standing and movement.

8. Proposed Walking Method

The recommended walking method for this robot design is:

Static Walking

In this method, one leg moves at a time while the other three legs remain on the ground.

Advantages:
High stability.
Suitable for small quadruped robots.
Reduces the possibility of falling.

Another possible future development is:

Trot Gait

In this method, diagonal legs move together, increasing walking speed while maintaining acceptable stability.

9. Expected Mechanical Problems

During operation, several mechanical problems may occur:

1. Insufficient Motor Torque

If the robot weight increases, the motors may not provide enough torque to move the legs.

2. Stability Problems

Incorrect center of gravity positioning may cause the robot to lose balance.

3. Joint Stress

Repeated movement can cause mechanical stress and wear on the joints.

4. Vibrations

Unequal motor movement or weak connections may create vibrations.

5. Power Consumption

Continuous leg movement requires an appropriate battery capacity.

10. Conclusion

A preliminary mechanical design of a quadruped robot dog was developed with dimensions of approximately 199.3 × 118 × 98.3 mm.

The robot uses a four-leg structure with 8 degrees of freedom, allowing basic walking and balancing movements. Metal gear servo motors with suitable torque are selected to drive the joints.

The design provides good stability due to the four-leg configuration and balanced center of gravity. Future improvements can include adding sensors, advanced control algorithms, and more efficient walking patterns to improve robot performance.
