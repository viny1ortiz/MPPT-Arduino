# Maximum Power Point Tracking (MPPT) controlled with Arduino

The MPPT is an algorithm used by solar charges to get the maximum power from a solar panel. On this university project, instead of using an actual solar panel the solar panel and the battery are simulated with simulating circuits.

# Simulating circuits

Before jumping straight to the project, let me introduce the circuits used to simulate the solar panel and battery.

**1. Solar Panel**

The solar panel is a simple constant current circuit, with a switch to set the current to 0.63A and 0.31A. These 2 different options represent as the higher current to be direct sunlight and the lower with cloudy weather.

![image](https://github.com/user-attachments/assets/5a3ca451-1d27-4589-b5e0-fba4938d64a1)

**2. Battery**

The battery simulator is simply a resistor of 3.3Ω which transfers electrical power into heat.

# Schematic

![image](https://github.com/user-attachments/assets/ae9e2e98-6e04-41a9-ac68-e3fffebafc77)
