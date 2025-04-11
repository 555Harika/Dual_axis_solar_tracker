# Dual_axis_solar_tracker
This project is a dual-axis solar tracking system designed to maximize solar energy capture by continuously aligning the solar panel with the direction of the sun. Using four LDRs and two servo motors, the system dynamically adjusts its position both horizontally and vertically to track sunlight throughout the day.

# Key Features:
Dual Axis Tracking – Adjusts solar panel in both horizontal and vertical directions.
Light-Based Control – Utilizes four LDRs to detect the brightest light source.
Energy Efficient – Maximizes solar exposure, increasing energy output.
Autonomous Operation – Fully automated with no manual intervention required.
Compact and Scalable – Ideal for small-scale solar projects or educational use.

# Components Used
Arduino UNO
4 × LDRs (Light Dependent Resistors)
2 × Servo Motors
Resistors
jumper wires
Solar panel

# How It Works
The four LDRs detect the intensity of sunlight from different directions.
The Arduino calculates the average light intensity from top, bottom, left, and right.
Based on these values, the servos rotate the solar panel toward the direction with the highest light intensity.
The process repeats continuously for optimal solar alignment.
