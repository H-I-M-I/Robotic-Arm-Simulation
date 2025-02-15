# **Dynamic Rotation - Robotic Arm Simulation**  

## **Overview**  
This project implements a **2D robotic arm simulation** using **Pygame**. The robotic arm consists of three links that smoothly transition to target angles using interpolation.  

## **Features**  
- Three-link **robotic arm** with smooth rotation.  
- Uses **trigonometry** for accurate joint positioning.  
- **Pygame-based visualization** for real-time movement.  
- Adjustable target angles for dynamic rotations.  

## **How It Works**  
1. The arm has three joints, each with a current and target angle.  
2. Angles update incrementally for a **smooth transition**.  
3. Uses **trigonometric calculations** to determine each link's endpoint.  
4. **Pygame handles rendering** and real-time updates.  

## **Future Improvements**  
- Add **user input** to control angles dynamically.  
- Implement **inverse kinematics** for better movement control.  
- Optimize performance for smoother rendering.  
