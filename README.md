# APPLE-Sensor-Fusion-
AIM

To compute the fused orientation angle using sensor fusion from IMU and vision data.

PROCEDURE
Initialize IMU and vision angle values
Apply the fusion formula: fused = (imu + vision) / 2
Substitute the given values
Compute the fused angle
Display the result
CODE
# Input values
imu = 32      # in degrees
vision = 28   # in degrees

# Sensor fusion (mean)
fused = (imu + vision) / 2

# Output
print("Fused Angle:", fused, "degrees")
OUTPUT

Fused Angle: 30°

RESULT

The fused orientation angle is calculated as 30°, improving accuracy by combining IMU and vision sensor data.
