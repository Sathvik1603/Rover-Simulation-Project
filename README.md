# 🚀 Mars World Simulation for Rover Project

Simulates a realistic Mars terrain in Gazebo Sim 8.9.0 using custom models and realistic Martian gravity, rocks, and Gale Crater terrain patches.

## 🗂 Project Structure
mars_world_project

mars_world.sdf

models

LargeRock_Fall

Small_Rock_Fall

Mars_Gale_Crater_Patch


## ✅ How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Sathvik1603/Rover-Simulation-Project.git
cd Rover-Simulation-Project

export GAZEBO_MODEL_PATH=$(pwd)/models:$GAZEBO_MODEL_PATH

gz sim mars_world.sdf
