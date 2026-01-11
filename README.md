# Smart Climate Control System
Digital Electronics Final Project, Sheen Handoo

# Project overview
For my final project, I built a Smart Climate Control System using a Raspberry Pi and a thermoelectric Peltier module. It senses temperature, decides whether to heat or cool, and uses power electronics (such as an H-bridge module) to drive the Peltier. Python code controls everything. This demonstrates embedded systems, digital logic, power control, and closed-loop feedback. 
(insert photo here)

# Inspiration and Initial Brainstorm
When coming up with a project, I was looking through my weather app for the next day and then I thought to myself, why not make a project based on temperature control. So I went with that idea and came up with a plan of having a fan on one side with a heater on the other of a box-like structure with a temperature sensor in the middle. After consulting others, I realized this idea was too simple, so after reaseard and help from Mr. Marc-Aurele, I was able to decide on using a Peltier device as my main control system and Thermocouples as my temperature sensors.

# Bill Of Materials and Part Descriptions
* Raspberry Pi 4: Main controller of my project
* Peltier devices: Thermoelectric cooling, used in Peltier devices, uses direct current passing through junctions of different conductors to create a temperature difference between two plates, effectively moving heat from a "cool side" to a "hot side." This solid-state method eliminates the need for liquid refrigerants, relying instead on metal conductors and heat sinks to dissipate thermal energy. YOu can see a visual of it in the image below. (Source 1)
    * <img width="480" height="237" alt="image" src="https://github.com/user-attachments/assets/5c0f767e-7736-4634-a8c6-25a8e00f1c54" />
* Thermocouples: A thermocouple is a temperature sensor made of two dissimilar metals joined at a junction that generates a voltage proportional to the temperature difference between that point and a known "cold junction" reference. Because different metal combinations offer varying sensitivities and ranges—such as the versatile Type K, which is the type I used in my project—careful selection of probe type and insulation is essential for accurate physiological or industrial monitoring (Source 2). I used an amplifier breakout board to measure and see the signals recieved from the thermocouple in order to use it in my code and integrate it into my project.
    * <img width="335" height="150" alt="image" src="https://github.com/user-attachments/assets/77577539-3c4e-4293-a103-c3997222d4bb" />
* BTS7960 43A (H-Bridge Module used in this project): The BTS 7960 is a compact, high-current motor driver that combines two power switches and an integrated controller into a single package, making it easy to connect directly to a microcontroller. It provides a highly efficient and safe solution for controlling motors by featuring built-in protections against issues like overheating and short circuits, while also reducing electromagnetic interference.
* Breadboard
* Jumper Wires
* Variable Power Supply

# 



