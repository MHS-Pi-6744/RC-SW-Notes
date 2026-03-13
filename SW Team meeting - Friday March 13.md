# SW Team meeting - Friday March 13

### What needs to be done for the next round of robot testing?

### Tests / Requiremests:

* Electrical check after rewiring
* All subsystems check after rebuild
* Autonomous
  * Need to prove it works and we are ready for Comp
  * Move hub in Witzel to match Comp field
* Drive practice  
  * Need driver controls sorted out & tested with 2 x-box controls - Irman does code and Logan & Matt with be driver reps
  * Button Box?  - need a decision
* Shooting tuning
  * Find a way to test shooting without hitting the ceiling
  * Determine shoot speed vs distance curve
* Intake tuning & test faster with half stop
* Climber stationary test - get it working 
* Climbing robot test
* Dynamic Drivebase testing
  * Assisted shooting 
    * Current config
    * With adapted angle calc
    * Supplementary camera for improved shooting positioning and as a backup to main shooting camera
  * Assisted fuel intake
    * Current config - need camera, code is ready but not tested - Leo
    * Test a intake button / intake assist interlock

### To-do ?:

* Shooter & feeder
  * Flywheel PID tuning and tune conveyer and wheels speed
* Intake
* * Make pivot go faster - Pete
  * Pivot Half position for dumping fuel in - Pete
* Climber
  * Support first testing - Irman
* Dyamamic Drivebase - Drivebase including vision based navigation and auto shoot tuning
  * Adapt auto set angle shoot to compensate for tag placement relative to center hub - Matt
  * Code for shoot speed vs distance feature in teleop and auto
* Driver station 
  * Finalize elastic layout - Matt with input from drive team
* Vision
  * Code for second shooting camera - Matt
* Autonomous
  * Clean up auto chooser (may need to modify RIO SD card)  Matt (or hand off?)
  * Look into reset odometry option in PathPlanner - Hamza?
* Object detection 
  * Plan needed - how to apply and test
* Local git for Comp - ? 

### Priority:

1. Driver controls 

2. Button box decision

3. Climber code to support testing

4. Intake half position

5. 
