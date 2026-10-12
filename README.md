# Rope-Runner
Rope Runner is a rope-climbing robot designed to move along a rope using a motor-driven gear and linkage mechanism. The project involved mechanical and electrical system integration, prototyping, and iterative design improvements to enhance movement, synchronization, and reliability.

# Rope Runner | Team Tesla

Rope Runner is a rope-climbing robot developed by Team Tesla at the University of Lagos for the SST Marker Space challenge.

As the **Electrical Lead**, I worked with the team to develop and test the electronics and support the integration of the robot's mechanical and control systems.

## The Robot

![Picture of Final Prototype](Picture%20of%20final%20prototype.jpg)

**Motion video:**

[Watch the Video of the Finished Project(rope-runner-thumbnail.jpg)](<Video%20of%20the%20proposed%20final%20prototype.mp4>)

## How It Works

A DC geared motor drives a system of gears and linkages that creates an alternating crawling motion. Four rope-contact points help support the robot as it moves along the rope.The electrical part involves using an ESP32 to control the motor through an L298N motor driver. The motor gets power from a 7.4V battery, while the ESP32 handles the control signals. We also used a rotary encoder to track movement and Bluetooth for wireless control.

## Electrical System

The planned control system uses:
- **ESP32 DevKit V1** for control
- **L298N motor driver** to control the motor
- **7.4 V lithium-ion battery** as the power source
- **Bluetooth** for phone control
- **Rotary encoder, potentiometer, voltage sensor, and RGB LED** for movement feedback, speed adjustment, battery monitoring, and status indication

The camera was not used in our final robot, so image capture and transmission were not part of the project.

## Challenges & What We Learned

We replaced cardboard gears with plastic gears to improve smoothness and synchronization. We also changed the chassis material after the cardboard prototype flexed, refined the linkage dimensions, and improved gear alignment to reduce friction and motor heating. Hook interference, chassis flex, and loose fasteners remained areas for improvement.

This project taught me how closely electrical performance depends on mechanical alignment, secure mounting, and repeated testing. As Electrical Lead, I contributed to the power and motor-control system while collaborating with the team on troubleshooting and prototype development. It also taught me the value of effort, commitment to work, and consistency. This has to be one of my best projects yet. See the final report below.

## Final Report

[Read the Team Tesla final report](Team-Tesla-Final-Report.pdf)

---

**Team Tesla · University of Lagos**
