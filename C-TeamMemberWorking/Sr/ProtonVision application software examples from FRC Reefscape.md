# ProtonVision application software examples from FRC Reefscape 
Team Code Repositories With PhotonVision in REEFSCAPE
# 1. ~[Team 233 REEFSCAPE 2025 Code \(Photon Vision included\)](https://github.com/ThePinkAlliance/FRC233-REEFSCAPE-Public?utm_source=chatgpt.com)~
This is the public repository for FRC Team 233’s 2025 REEFSCAPE robot code. It includes:
* Subsystems such as drivetrain, intake, shooter, climber, etc.
* A Photon Vision (PhotonVision) aided localization subsystem.
* Modular command structure and telemetry/logging via AdvantageKit. 

⠀This is a concrete example of how one team used PhotonVision within their robot code for vision processing and pose estimation.
👉 Look in:
* src/main/java/frc/robot/subsystems for Vision subsystem integration
* PhotonVision configuration and how it feeds data into NetworkTables

# 2. Team 1710 2025 Robot Code (Java + PhotonVision)
Team 1710’s 2025 robot code uses PhotonVision alongside:
* 3 Orange Pi 5s for vision processing
* SDS Mk4i swerve modules
* PathPlanner for autonomous movement
* PhotonVision handling target detection/pose estimation data sent into robot code for decision making. 

⠀This repository is especially good if you want to see how a larger multi-camera setup feeds into a command-based robot codebase.

# 3. ~Team 4079 Reefscape2025 (Java/Kotlin)~
Source code archive for Team 4079’s 2025 robot code. While this one is archived and might not have ready PhotonVision code visible immediately:
* You can search for “photon” or “PhotonCamera” in the repo to find how vision is integrated.
* Great example of Kotlin + Java mixed robot code from a competition team. 

# 4. Other REEFSCAPE Repositories You Can Explore
These may not explicitly document PhotonVision usage, but often include robot code where vision is integrated or can be added:
* 1757 WestwoodRobotics/2025-Reefscape: Python-based robot code (RobotPy) — a good reference for converting Java PhotonVision logic to Python. 
* FRC-2357/FRC-2025: Reefscape season code base where you can search for vision config directories (PhotonSettings/Calibrations). 

⠀
# PhotonVision Vendor & Example Repositories
These aren’t team repositories but show core library examples:
# PhotonVision Official Examples
* The photonlib-examples repo contains basic usage patterns (e.g., get target info from camera, use PhotonPoseEstimator, etc.). 

PhotonVision documentation includes general sample patterns you can adapt:
* Aiming at a target
* Combining aiming and range estimation
* Using pose estimation with WPILibThese are *not specific to REEFSCAPE*, but directly relevant for implementing vision code in any season. 

⠀
# Tips for Using These Examples
## Vision Data Integration in Robot Code
Most teams:
* Use PhotonCamera / pipelines in code
* Retrieve vision results through NetworkTables
* Feed that into autonomous commands or alignment routines

⠀In Java (WPILib), typical photonvision usage involves:

### PhotonCameracamera = new PhotonCamera("cameraName");

// In your periodic method:
var result = camera.getLatestResult();
if (result.hasTargets()) {
    var target = result.getBestTarget();
    double tx = target.getYaw();    // horizontal offset
    double ty = target.getPitch();  // vertical offset
    double distance = calculateDistance(target); // custom example
    // Use these to drive auto alignment
}
*This pattern appears in many team repos (search for* PhotonCamera*/*getLatestResult*).*

# Summary
Useful starting points for FRC REEFSCAPE vision code examples:
* Team 233’s REEFSCAPE repository (with PhotonVision integrated) 
* Team 1710 2025 robot code (PhotonVision + multi-camera config) 
* Team 4079 and others’ repos where you can search for photon integration 
* PhotonVision vendor examples & official docs for basic vision usage patterns 

