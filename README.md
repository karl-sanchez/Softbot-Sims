# Softbot-Sims

These are the LIGGGHTS simulations for the Area of Effect Soft Bots team. Simulations are each in a specific folder.  Their descriptions are as follows:

01_CascadeSim: this inserts particles and lets them fall to the floor under the force of gravity. This one is the simplest, so those learning LIGGGHTS should start here

02_ColliderSim: this model imports CAD (a box) as an .stl file and has the particles interact with the box by falling on it.

03_SimplePlateSim: early version of plate insertion. See later simulations for better implementation of this scenario

04_Launcher: this is the one I used for the final report. A bucket is filled, micro-g is turned on, and the bucket launches the particles

05_ScoopSim: similar to plate sim, but with added horizontal translation. See sim 06 for a better version

06_Plate_Restart_and_LW_validation: this folder has the plate insertion sim I used in the report. A subfolder called SandSim has the same simulation modified to verify our model with the Luth-Wismer Model.
