This Arduino sketch uses the AFMotor and Servo libraries to control a robot with four DC motors. The motor movements are controlled based on commands received through the HC05 module

    Motor Initialization:
        Four DC motors are initialized with AF_DCMotor objects.

    Setup Function:
        communication is started.
        Motors are set to a speed of 150.

    Loop Function:
        Reads serial input and executes corresponding motor control commands.

    Motor Control Functions:
        right(), left(), reverse(), forward(), stop() control motor directions and actions.
