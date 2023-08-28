# 1. Research papers related to robotic vehicles

## SoK
- SoK: A Minimalist Approach to Formalizing Analog Sensor Security, S&P'20.
- SoK: Security and Privacy in the Age of Commercial Drones, S&P'21.
- SoK: Rethinking Sensor Spoofing Attacks against Robotic Vehicles from a Systematic View, Euro S&P'23.


## Electromagnetic field injection attacks
- Detection of Electromagnetic Signal Injection Attacks on Actuator Systems, RAID'22.
- Paralyzing Drones via EMI Signal Injection on Sensory Communication Channels, NDSS'23.
- Physical-Layer Attacks Against PulseWidth Modulation-Controlled Actuators, USENIX security'22.


## GPS spoofing
- All Your GPS Are Belong To Us: Towards Stealthy Manipulation of Road Navigation Systems, USENIX security'18.
- Crowd-GPS-Sec: Leveraging Crowdsourcing to Detect and Localize GPS Spoofing Attacks, S&P'18.
- Cryptography Is Not Enough: Real-time Location Spoofing of Authenticated GNSS Signals, arxiv.
- SemperFi: Anti-spoofing GPS Receiver for UAVs, NDSS'22.


## Optical flow spoofing
- Controlling UAVs with Sensor Input Spoofing Attacks, WOOT'16.


## Sound noise on gyroscope
- Rocking Drones with Intentional Sound Noise on Gyroscopic Sensors, USENIX security'15.
- WALNUT: Waging Doubt on the Integrity of MEMS Accelerometers with Acoustic Injection Attacks, EuroS&P'17.
- SONIC GUN TO SMART DEVICES YOUR DEVICES LOSE CONTROL UNDER ULTRASOUND/SOUND, BlackHat'17.
- Injected and Delivered: Fabricating Implicit Control over Actuation Systems by Spoofing Inertial Sensors, USENIX Security'18.
- Un-Rocking Drones: Foundations of Acoustic Injection Attacks and Recovery Thereof, NDSS'23.


## Depth camera spoofing
- DoubleStar: Long-Range Attack Towards Depth Estimation based Obstacle Avoidance in Autonomous Systems, USENIX security'22.


## Sensor spoofing simulation
- Poster: Automated Discovery of Sensor Spoofing Attacks on Robotic Vehicles, CCS'22.


## RV swarm
- Swarmbug: Debugging Configuration Bugs in Swarm Robotics, FSE'21.
- Vision-based Drone Flocking in Outdoor Environments, IEEE Robotics and Automation Letters'21.
- SWARMFLAWFINDER: Discovering and Exploiting Logic Flaws of Swarm Algorithms, S&P'22.
- Privacy-Preserving Trajectory Matching on Autonomous Unmanned Aerial Vehicles, ACSAC'22.
- SUAVE: An Exemplar for Self-Adaptive Underwater Vehicles, SEAMS'23.
- Self-Adaptive Mechanisms for Misconfigurations in Small Uncrewed Aerial Systems, SEAMS'23.


## ROS
- PhysFrame: Type Checking Physical Frames of Reference for Robotic Systems, FSE'21.
- RoboFuzz: Fuzzing Robotic Systems over Robot Operating System (ROS) for Finding Correctness Bugs, FSE'22.
- On the (In)Security of Secure ROS2, CCS'22.

## Forensic
- From Control Model to Program: Investigating Robotic Aerial Vehicle Accidents with MAYDAY, USENIX security'20.
- RVPLAYER: Robotic Vehicle Forensics by Replay with What-if Reasoning, NDSS'22.


## Attack detection/recovery
- Sensor CON-Fusion: Defeating Kalman Filter in Signal Injection Attack, AsiaCCS'18.
- Detecting Attacks Against Robotic Vehicles: A Control Invariant Approach, CCS'18.
- SAVIOR: Securing Autonomous Vehicles with Robust Physical Invariants, USENIX security'20.
- Replay-based Recovery for Autonomous Robotic Vehicles from Sensor Deception Attacks, arxiv.


## Discovering bugs
- Cyber-Physical Inconsistency Vulnerability Identification for Safety Checks in Robotic Vehicles, CCS'20.
- Control Parameters Considered Harmful: Detecting Range Specification Bugs in Drone Configuration Modules via Learning-Guided Search, ICSE'22.

## Privacy
- Privaros: A framework for privacy-compliant delivery drones, CCS'20.

# 2. Research papers related to industrial control system (ICS)

## SoK
- SoK: Attacks on Industrial Control Logic and Formal Verification-Based Defenses, Euro S&P'21
  
## Anomaly detection with machine learning-based methods
- Anomaly detection for a water treatment system using unsupervised machine learning, ICDMW'17
- Anomaly Detection in ICS based on Data-history Analysis, EICC'20
- Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering, KDD'21
- Log-Based Anomaly Detection With Robust Feature Extraction and Online Learning, T-IFS 2021
- AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis, IEEE TRANSACTIONS ON MOBILE COMPUTING 2022

## Anomaly detection with program analysis
- A trusted safety verifier for process controller code, NDSS'14
- AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis, RAID'21
- SCAPHY: Detecting Modern ICS Attacks by Correlating Behaviors in SCADA and PHYsical, S&P'23
    
## Anomaly detection with side channels
- Anomoly Detection for PLC Based on Magnetic Side Channel, EI2'20

## Invariant-based (a.k.a. policy-based) methods
- Blocking unsafe behaviors in control systems through static and dynamic policy enforcement, DAC'15
- A systematic framework to generate invariants for anomaly detection in industrial control systems, NDSS'19
- PLC-Sleuth: Detecting and Localizing PLC Intrusions Using Control Invariants, RAID'20
- Control Behavior Integrity for Distributed Cyber-Physical Systems, ICCPS'20
- Detecting and localizing PLC intrusions using control invariants, IEEE Internet of Things Journal, 2022
- Exploiting the Temporal Behavior of State Transitions for Intrusion Detection in ICS/SCADA, IEEE Access 2022
- Anomaly Detection based on Robust Spatial-temporal Modeling for Industrial Control Systems, MASS 2022
  
## Formal method
- A Temporal Logic for Programmable Logic Controllers, Automatic Control and Computer Sciences 2021

## Discovering and patching bugs and vulnerabilities
- Towards automated safety vetting of PLC code in real-world plants, S&P'19
- Detecting Insecure Code Patterns in Industrial Robot Programs, ASIACCS'20
- ICSFuzz: Manipulating I/Os and Repurposing Binary Code to Enable Instrumented Fuzzing in ICS Control Applications, USENIX Security'21
- Empirical Study of PLC Authentication Protocols in Industrial Control Systems, SPW'21
- Automated Runtime Mitigation for Misconfiguration Vulnerabilities in Industrial Control Systems, RAID'22
- ICSPatch: Automated Vulnerability Localization and Non-Intrusive Hotpatching in Industrial Control Systems using Data Dependence Graphs, USENIX Security'23
  
## Attacks 
- Constrained Concealment Attacks against Reconstruction-based Anomaly Detectors in Industrial Control Systems, ACSAC'20


# 3. Research papers related to autonomous vehicles

## Discovering bugs
- Av-fuzzer: Finding safety violations in autonomous driving systems, ISSRE'20.
- Drivefuzz: Discovering autonomous driving bugs through driving quality-guided fuzzing, CCS'22.
- Doppelganger Test Generation for Revealing Bugs in Autonomous Driving Software, ICSE'23.
- Discovering Adversarial Driving Maneuvers against Autonomous Vehicles, USENIX security'23.
