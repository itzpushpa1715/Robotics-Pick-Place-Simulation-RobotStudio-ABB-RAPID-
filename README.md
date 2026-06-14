Designed and programmed a robot application in ABB RobotStudio that picks plates from a worktop and places them onto a conveyor, transferring six pieces per cycle before the program and simulation can be restarted.
Key highlights:

Built the full RAPID program structure with modular subroutines for Home, Pick, and Place operations, called sequentially from the main program for clarity and reusability.
Taught and refined robot target points (home, pick-up, export, plus auxiliary via-points) to ensure smooth, efficient, and collision-free trajectories.
Implemented linear (MoveL) approach and retreat motions at the pick-up and place points, using slow, controlled speeds for precise positioning, while using faster joint moves (MoveJ) for the home and transit paths.
Configured I/O control and input verification (e.g., gripper signals and line sensor checks) to synchronize gripping actions with the Smart Component logic.
Used a Smart Component with a Line Sensor to simulate accurate gripping behavior and piece transfer from the worktop to the conveyor.
Validated the complete cycle through simulation, confirming correct trajectory execution, gripping/release sequencing, and repeatable six-piece cycles.

This project strengthened my practical skills in RAPID programming, robot target teaching, motion planning (MoveJ/MoveL), I/O signal handling, and simulation-based validation using ABB RobotStudio.
