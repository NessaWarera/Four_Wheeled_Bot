# ROBOT SIMULATION PROJECT
This project aims to launch and simulate a robot in Gazebo. This repository serves as a guide for developing and simulating a robot. It highlights all the steps that should be followed to achieve the desired result.

## STEP 1: CAD MODELLING
Design your robot using any CAD tool of your preference. Assemble the robot and ensure that it is done correctly. Properly define the links and joints and ensure that the parts are properly separated in the assembly.

## STEP 2: URDF GENERATION
The next step is to generate the URDF. This will depend on the CAD tool used because some like On Shape and Fusion 360 can generate URDFs by downloading an add-on. If your CAD tool cannot generate the URDF, use Blender. Export the file to Blender in your desired format and use the Phobos add-on to generate the URDF. Ensure that all the links, joints and geometry are properly defined. Download the URDF and meshes. 

## STEP 3: SPAWNING THE ROBOT

