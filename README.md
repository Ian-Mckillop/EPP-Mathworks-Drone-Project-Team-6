# Drone Payload Capacity and Structural Design Analysis Project
Team 6 - JINB Drone Makers

## Objective
The goal of this project was to design two arms and maximize the payload capacity while maintaining the minimum structural integrity. We were provided with various materials and parameters to determine the following things:

1. A thrust-to-weight analysis to ensure our drone arms can withstand a max payload
2. Finite Element Analysis (FEA) to determine the effects of displacement, stress, and factor of safety under the motor and payload loads.

Out of our two drone arm designs, our TArm Design using Birch was the most effective. It achieves a max payload of **0.96 kg**.

## Repository Content

| File/Folder | Description |
|---|---|
| Matlab Scripts | MATLAB code for thrust-to-weight analysis and FEA |
| Drone Arm (Tube).stl | CAD model for Tube arm design |
| TArmCAD.stl | CAD model for T-arm design |
| Teamwork Agreement | Team roles and working agreement |

## Required Toolboxes / Dependencies

- MATLAB
- Partial Differential Equation Toolbox (required for FEA)

## How to Run

1. Clone this repository.
2. Open MATLAB and set the repository folder as your current working
   directory.
3. Open the Final Live Script in MATLAB.
4. Run the Live Script. This will provide you with the thrust-to-weight analysis and FEA for both designs. 

## Design Summary

| Design | Material | Max Payload (kg) | Max Stress (Pa) | Factor of Safety |
|---|---|---|---|---|
| Tube Arm | Birch | 0.92 kg | 5.0e+06 | 16 |
| T Arm | Birch | 0.96 kg | 1.53e+07 | 5.2 |

![Birch T Arm](https://github.com/Ian-Mckillop/EPP-Mathworks-Drone-Project-Team-6/blob/main/Images/BirchTArmFEAVisualization.png)

![Birch Tube Arm](https://github.com/Ian-Mckillop/EPP-Mathworks-Drone-Project-Team-6/blob/main/Images/BirchTubeArmFEAVisualization.png)