# Open-Source Stepper-Driven 3D Printable Gripper with Quick-Change Mechanism

A fully 3D-printable robotic gripper featuring **stepper motor + multi-stage worm gear actuation** and **tool-free quick-change** capability. Designed for modular robotics applications with simulation-ready resources.

---

## Project Contents

### 1. **Mechanical Design** *(Modifiable & Printable)*
- **Gripper Assembly**: 
  - SolidWorks 2024 files (`.SLDPRT`/`.SLDASM`) + STEP formats
  - Optimized STLs for FDM printing (no supports needed for critical parts)
- **Quick-Change Mechanism**: 
  - Magnetic/mechanical locking design (SW2024 + STEP)
- **Multi-Stage Worm Gear Transmission**:
  - High reduction ratio for torque amplification
  - Self-locking property integrated

### 2. **Control System** *(CAN Bus)*
- **Firmware Features**:
  - Position control (closed-loop with step counting)
  - Torque control (current sensing via load cell)
  - Gripper distance ↔ stepper angle calibration curve
- **Supported Hardware**:
  - STM32 (C, HAL library examples),USB to can tool(python)

### 3. **Simulation** *(pybullet)*
- **URDF Model**: 
  - Gripper jaw symmetrical binding control
  - The relationship between the contact force and the torque of the joint
- **BOM (Bill of Materials)**:
  - Printable parts list (filament estimates)
  - Off-the-shelf components (links to suppliers)

---

## Repository Structure
