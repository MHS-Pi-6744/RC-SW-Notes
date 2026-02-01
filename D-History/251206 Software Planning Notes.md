# Software Planning Notes 6Dec2025
Here’s what I understood from our work on Saturday, let me know if I missed something or got something wrong. Software team: please feel free to make changes on the shared google doc.
## Active Projects:
### A quick one to fit in before the Reefscape robot is dismantled
* Test Climber with Matt’s code — Matt, Pete, Irman
  * A quick test to see if it will climb
  * Climber update to use buttons for each position — Pete, Irman
    * Much of the work is done but hasn’t been tested - work put on hold so team can concentrate on preparing for the REBUILT season
### 1st Priority
- Electrical test bed software -- *Software:* Matt, Pete -- *Electrical:* John?
  - Stationary testing platform
  - Drive-base testing platform
- Vision system & APRIL tags -- *Software:* Tommy, Irman -- *Electrical:* Logan
  - Camera and Rubik Pi set up and programming -- Logan, Irman
  - PhotonVision install and setup — Tommy, Irman
  - APRIL tags — Research how to read and use — Tommy
### 2nd Priority
* LaserCAN range sensor
  * Logan got it working with it being read by software on a laptop — Robot software to read the sensor will be needed
  * Will develop range finding software later when the application is defined for REBUILT
* Clean up Reefscape branches - 
  * main and development branches — keep 
  * f-climber - branch with Matt’s climber that should be tested — keep
  * Peber-Climber - this branch has the latest changes for position buttons — keep for now
  * training-climber - branch not needed Sr will delete
  * feat_pathPlanner_preGRC - branch is 5 commits ahead of development — Leo needs to sort out what needs to be done with these and decide if the branch should be deleted. (It might be needed for the drive-base testbed)
  * feat_colorSensor_preGRC - branch has only 1 commit ahead of develop and now work is planned — Sr will save the changes in the commit and delete the branch
  * feat-auto-comp - Tommy will sort out what should be done with this branch - delete or keep for drive-base testbed
  * f-simulation - holding a little work from last spring, Matt will sort out what to do with the 3 commits and delete the branch 
### 3rd Priority
* Set up a local origin for repo’s — Matt and Sr are looking at this
  * Not critical to have this for now, team will continue using Github; but will need for comp when wifi isn’t allowed in the pits 
* Simulation — team should decide a path on this after the electrical test beds are operational
## Some of the progress made on Saturday:
* 6744-Testbed repo created from 6744-Reefscape-Development with 2 branches for Drivebase and Stationary
* Rubik Pi is set up operating Linux, ready for PhotonVision installation
* Research on PhotonVision

