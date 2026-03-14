# SW team planning notes  - Friday March 13
## What needs to be done for the next round of robot testing?
## Tests / Requirements:
* Electrical check after rewiring
* All subsystems check after rebuild
* Autonomous
  * Need to prove it works and we are ready for Comp
  * Move hub in Witzel to match Comp field
* Drive practice
  * Need driver controls sorted out & tested with 2 xbox controllers - Irman does code and Logan & Matt with be driver reps
  * Button Box? - Decision has been made to wait on this.
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

⠀To-do:
* Shooter & feeder
  * Flywheel PID tuning and tune conveyer and wheels speed
  * Increase shooting rate
* Intake
  * Make pivot go faster - Pete
  * Pivot Half position for dumping fuel in - Pete
* Climber
  * Support first testing - Irman
* Dynamic Drivebase - Drivebase including vision based navigation and auto shoot tuning
  * Adapt auto set angle shoot to compensate for tag placement relative to center hub - Matt
  * Code for shoot speed vs distance feature in tele-op and auto
  * Test code for vision assisted intake test - Leo
  * Code for  intake button / intake assist interlock - Pete & Leo need Logan input on requirements
* Driver station
  * Set up code to implement Comp driver control configuration - Irman
  * Finalize elastic layout - Matt with input from drive team
* Vision
  * Code for second shooting camera - Matt
* Autonomous
  * Clean up auto chooser (may need to modify RIO SD card) Matt (or hand off?)
  * Look into the reset odometry option in PathPlanner - Hamza
* Object detection
  * Plan needed - how to apply and test
* Local git for Comp - 
  * Take a look at a USB git server set up - Matt & Irman

⠀Software Priority:
1. Driver controls configuration and coding (with two xbox controllers)
2. Climber implementation - code and testing
3. Intake half position and speed up
4. Support for increased shooting rate - several systems are involved
5. Dynamic Drivebase vision assisted intake
6. Dynamic Drivebase vision assisted shooting accuracy improvements

⠀



