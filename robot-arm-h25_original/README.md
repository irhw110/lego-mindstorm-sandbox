### Robot Arm H25

<img src="header.jpg" alt="alt text" width="300"/>

**Building Instructions:** [Link to Building Instructions](https://le-www-live-s.legocdn.com/sc/media/lessons/mindstorms-ev3/building-instructions/ev3-model-core-set-robot-arm-h25-56cdb22c1e3a02f1770bda72862ce2bd.pdf)

**Demo Video:**
https://youtu.be/RfHfBiq-8kU

**Experiment Setup:**
- Uses 2 large motors each for base-rotator & arm-joint
- 1 medium motor for the pick-arm grappler
- 1 Color sensor for arm-joint limiter
- 1 Touch sensor for base-rotator limiter
- 1 Touch sensor for triggering-action control from the user

**Program Description:**
1. During startup, the robot will reset its position into ready-mode.
2. When the button sensor on INPUT 3 is pressed, the action is triggered:
    - The arm will descend to pick the object up.
    - Rotate 90 degrees and place the object.
    - Return to the ready-mode position.
3. Since the pick-arm grappler doesn't have a sensor to limit its movement, it needs manual configuration using the left-right buttons on the BRICK CORE.
4. The center button on the BRICK CORE can be used to cancel any actions and reset the position.

**Challenges Faced:**
- Limited number of sensors is restricting the robot's possible movements.
- With only 3 degrees of freedom, the robot's ability to perform complex object-picking tasks is limited.
