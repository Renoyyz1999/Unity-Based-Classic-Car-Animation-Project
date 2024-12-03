# Unity-Based-Classic-Car-Animation-Project  

**Final Project: Unity-Based Classic Car Animation Project**  
**Name:** Yanzhi Yao  
**Student ID:** 301586422  

## Overview  
This project is a Unity-based car simulation featuring realistic driving mechanics, a thrilling Drift Mode, and an entertaining Dance Mode with ten unique animations. The project combines physics-based principles, procedural animation, and creative scripting to deliver an engaging user experience.  

## System Requirements  

- **Operating System:**  
  - Windows 11  (Project developed using Window 11)
  - macOS (Also Tested on MacBook Pro with M1 Pro chip)  

- **Unity Version:** Unity 2021.3.45f1  

- **Car Asset:** [Retro Cartoon Cars - Cicada](https://assetstore.unity.com/packages/3d/vehicles/land/retro-cartoon-cars-cicada-96158?aid=1101l9Tam)  

### Notes for macOS system:  
- The project has been tested on a MacBook Pro with an M1 Pro chip.  
- Use the same Unity version (Unity 2021.3.45f1).  
- If Unity Hub prompts a window asking to refactor the project, click **Yes**. The project will then run identically to its behavior on a Windows system.  


## Setup Instructions  
1. Clone the project repository from GitHub:  
   [Unity-Based-Classic-Car-Animation-Project](https://github.com/Renoyyz1999/Unity-Based-Classic-Car-Animation-Project/tree/main)  
   ```bash
   git clone https://github.com/Renoyyz1999/Unity-Based-Classic-Car-Animation-Project.git

2. Open Unity Hub and ensure Unity 2021.3.45f1 is installed.
3. Open the project in Unity Hub using Unity 2021.3.45f1.
4. Press the "Play" button in Unity to start the simulation.

## Car Control Instructions  

### **Driving Mode**  
- **W:** Move forward.  
- **S:** Move backward.  
- **A:** Turn left.  
- **D:** Turn right.  
- **Spacebar:** Apply brake.  

### **Drift Mode**  
- **Toggle Drift Mode:** Press `Q`.  
- **Drift Functionality:**  
  - Activates controlled drifting.  
  - Enhanced acceleration and turning angles.  
  - Rear-wheel drive for realistic drift behavior.  

### **Dance Mode**  
- **Toggle Dance Mode:** Press `E`.  
- **Select Dance Styles:** Use numeric keys (1-9, 0) to execute one of 10 dance styles:  
  1. **Bounce:** Car jumps vertically, mimicking low-rider effects.  
  2. **Rock:** Alternates suspension heights on the left and right sides.  
  3. **Right Lift:** Gradually raises the right-side wheels.  
  4. **Left Lift:** Gradually raises the left-side wheels.  
  5. **Front Lift:** Lifts the front wheels while keeping the rear stable.  
  6. **Rear Lift:** Lifts the rear wheels for a nose-down effect.  
  7. **Zigzag:** Alternates suspension heights diagonally for a zigzag motion.  
  8. **Three-Wheel:** Balances the car on three wheels, cycling through configurations.  
  9. **Wave:** Creates a cascading wave-like effect across all four wheels.  
  10. **Crazy Dance:** Combines chaotic motion patterns for an entertaining effect.  
- **Stop Dancing:** Press `X` to exit the current dance routine.  

---

## Features  

1. **Driving Mechanics:**  
   - Simulates real-world driving using Unity's physics engine.  
   - WheelCollider ensures accurate handling of forces, friction, and terrain interaction.  
   - Smooth steering and intuitive input mapping.  

2. **Drift Mode:**  
   - Provides a thrilling drifting experience.  
   - Rear-wheel friction adjustment for controlled slides.  
   - Increased steering angle and acceleration for responsive control.  

3. **Dance Mode:**  
   - Unique animation routines implemented via coroutines.  
   - Ten distinct dance styles with creative effects.  
   - Dynamic wheel suspension adjustments driven by procedural animations.  
   - Smooth transitions and synchronized motion for visual appeal.  

4. **User-Friendly Controls:**  
   - Easy-to-use input system for toggling modes and selecting features.  
   - Numeric key support for selecting specific dance styles.  

