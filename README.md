# Amazon Obstacle Detection Robot

## Aim
To detect obstacles using depth sensor data and stop the robot when distance is less than 0.5 meters.

## Dataset
Intel RealSense Depth Dataset

## Procedure
1. Load depth values
2. Read distance
3. Compare with threshold (0.5 m)
4. Stop robot if obstacle detected
5. Display output

## Algorithm
Step 1: Start
Step 2: Read distance value
Step 3: Set threshold = 0.5 m
Step 4: If distance < threshold
            velocity = 0
            Robot Halted
        Else
            Robot Moving
Step 5: Stop

## Output
Robot Halted

## Industry Application
Amazon Fulfillment Robots
