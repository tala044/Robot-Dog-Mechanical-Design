# Mechanical Calculations

## 1. Assumptions

The following assumptions are used for a simple mechanical estimation:

- Estimated robot mass: 2 kg
- Number of legs: 4
- Gravity: 9.81 m/s²
- Approximate upper leg length: 0.10 m
- Approximate distance from the joint to the center of mass: 0.10 m

## 2. Weight Calculation

The total weight of the robot can be estimated using:

W = m × g

Where:

- W = Weight
- m = Mass
- g = Gravity

Calculation:

W = 2 × 9.81

W = 19.62 N

Therefore, the estimated total weight of the robot is:

**19.62 N**

## 3. Estimated Load on Each Leg

Assuming the robot's weight is distributed equally across four legs:

Load per leg = Total Weight / Number of Legs

Calculation:

Load per leg = 19.62 / 4

Load per leg = 4.905 N

Therefore, each leg is estimated to support approximately:

**4.91 N**

## 4. Joint Torque Calculation

The required torque can be estimated using:

T = F × d

Where:

- T = Torque
- F = Force
- d = Distance from the joint

Using the estimated load per leg:

T = 4.905 × 0.10

T = 0.4905 N·m

Therefore, the estimated minimum torque required at the joint is:

**0.49 N·m**

## 5. Servo Motor Consideration

The calculated torque represents an ideal minimum estimate. In a real robot, additional torque is required because of:

- Dynamic movement
- Leg weight
- Friction
- Uneven weight distribution
- Acceleration
- Safety margin

Therefore, a servo motor with a higher torque rating than the calculated minimum should be selected.

## 6. Center of Gravity

For better stability, the center of gravity should remain close to the center of the robot body.

The four legs should create a stable support area around the center of gravity.

A stable robot design should:

- Keep the body balanced between the four legs
- Distribute weight as evenly as possible
- Avoid excessive weight on one side
- Keep the center of gravity low when possible

## 7. Stability Consideration

The robot is most stable when the center of gravity remains inside the support area created by the legs.

During walking, the robot must shift its weight carefully to avoid moving the center of gravity outside the support area.

## Conclusion

These calculations provide a simple estimation of the mechanical requirements for the robotic dog.

The estimated results are:

- Total robot weight: **19.62 N**
- Estimated load per leg: **4.91 N**
- Estimated minimum joint torque: **0.49 N·m**

These values are simplified estimates and would need further testing and refinement in a real physical robotic system.
