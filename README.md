<h1> :newspaper: Welcome a reading list for cyber-physical systems (CPS) security.</h1>
<b>Index</b> <br>
<a href="https://github.com/KimHyungSub/CPS-papers#1-research-papers-related-to-robotic-vehicles-airplane">1. Robotic vehicles (RVs)</a> :airplane: <br>
<a href="https://github.com/KimHyungSub/CPS-papers#2-research-papers-related-to-industrial-control-system-ics-factory">2. Industrial control systems (ICSs)</a> :factory: <br>
<a href="https://github.com/KimHyungSub/CPS-papers#3-research-papers-related-to-autonomous-vehicles-red_car">3. Autonomous vehicles (AVs)</a> :red_car: <br>
<a href="https://github.com/KimHyungSub/CPS-papers#4-research-papers-related-to-satellites-satellite">4. Satellites</a> :satellite: <br>
<a href="https://github.com/KimHyungSub/CPS-papers#5-other-research-topics-related-to-cps">5. Other research topics related to CPS</a><br>

# 1. Research papers related to robotic vehicles :airplane:

## 1-1) SoK/Survey
- SoK: A Minimalist Approach to Formalizing Analog Sensor Security, S&P'20.
- SoK: Security and Privacy in the Age of Commercial Drones, S&P'21.
- SoK: Rethinking Sensor Spoofing Attacks against Robotic Vehicles from a Systematic View, Euro S&P'23.
- A Survey on Security and Privacy Issues of UAVs, Computer Networks'23.


## 1-2) Electromagnetic field injection (EMI) attacks
- Introduction to the special issue on high-power electromagnetics (HPEM) and intentional electromagnetic interference (IEMI), IEEE Transactions on electromagnetic compatibility, 2004.
- Detection of Electromagnetic Signal Injection Attacks on Actuator Systems, RAID'22.
- Wireless manipulation of serial communication, AsiaCCS'22.
- Physical-Layer Attacks Against PulseWidth Modulation-Controlled Actuators, USENIX security'22.
- Signal Injection Attacks against CCD Image Sensors, AsiaCCS'22
- Paralyzing Drones via EMI Signal Injection on Sensory Communication Channels, NDSS'23.
- GlitchHiker: Uncovering Vulnerabilities of Image Signal Transmission with IEMI, USENIX Security'23
  
### 1-2-1) Countermeasures against EMI attacks
  - Electromagnetic interference, Electronics Computer Technology, 2011. (EMI filters such as L-C, Pi, T filters)
  - Ghost talk: Mitigating EMI signal injection attacks against analog sensors, S&P'13. (Shielding and differential signaling)
  - Pycra: Physical challenge-response authentication for active sensors under spoofing attacks, CCS'15. (Low-pass filter)
  - Electromagnetic Signal Injection Attacks on Differential Signaling, arXiv, 2022. (Differential signaling)
  - Wireless manipulation of serial communication, AsiaCCS'22. (Twisted pair and coaxial cables)
### 1-2-2) Tools
  - <a href="https://www.ansys.com/products/electronics/ansys-hfss" target="_blank">Electromagnetic Field Simulator</a>


## 1-3) GPS/GNSS spoofing
- All Your GPS Are Belong To Us: Towards Stealthy Manipulation of Road Navigation Systems, USENIX security'18.
- Crowd-GPS-Sec: Leveraging Crowdsourcing to Detect and Localize GPS Spoofing Attacks, S&P'18.
- Cryptography Is Not Enough: Real-time Location Spoofing of Authenticated GNSS Signals, arxiv.
- SemperFi: Anti-spoofing GPS Receiver for UAVs, NDSS'22.
- Cryptography Is Not Enough: Relay Attacks on Authenticated GNSS Signals, arXiv (2022).


## 1-4) Optical flow spoofing
- Controlling UAVs with Sensor Input Spoofing Attacks, WOOT'16.


## 1-5) Sound noise on gyroscope
- Rocking Drones with Intentional Sound Noise on Gyroscopic Sensors, USENIX security'15.
- WALNUT: Waging Doubt on the Integrity of MEMS Accelerometers with Acoustic Injection Attacks, EuroS&P'17.
- SONIC GUN TO SMART DEVICES YOUR DEVICES LOSE CONTROL UNDER ULTRASOUND/SOUND, BlackHat'17.
- Injected and Delivered: Fabricating Implicit Control over Actuation Systems by Spoofing Inertial Sensors, USENIX Security'18.
- Un-Rocking Drones: Foundations of Acoustic Injection Attacks and Recovery Thereof, NDSS'23.


## 1-6) Depth camera spoofing
- DoubleStar: Long-Range Attack Towards Depth Estimation based Obstacle Avoidance in Autonomous Systems, USENIX security'22.


## 1-7) Sensor spoofing simulation
- Poster: Automated Discovery of Sensor Spoofing Attacks on Robotic Vehicles, CCS'22.


## 1-8) RV swarm
- Swarmbug: Debugging Configuration Bugs in Swarm Robotics, FSE'21.
- Vision-based Drone Flocking in Outdoor Environments, IEEE Robotics and Automation Letters'21.
- SWARMFLAWFINDER: Discovering and Exploiting Logic Flaws of Swarm Algorithms, S&P'22.
- Privacy-Preserving Trajectory Matching on Autonomous Unmanned Aerial Vehicles, ACSAC'22.
- SUAVE: An Exemplar for Self-Adaptive Underwater Vehicles, SEAMS'23.
- Self-Adaptive Mechanisms for Misconfigurations in Small Uncrewed Aerial Systems, SEAMS'23.
- SwarmFuzz: Discovering GPS Spoofing Attacks in Drone Swarms, DSN'23.
- Lightweight Privacy-Preserving Proximity Discovery for Remotely-Controlled Drones, ACSAC'23

## 1-9) ROS
- PhysFrame: Type Checking Physical Frames of Reference for Robotic Systems, FSE'21.
- RoboFuzz: Fuzzing Robotic Systems over Robot Operating System (ROS) for Finding Correctness Bugs, FSE'22.
- On the (In)Security of Secure ROS2, CCS'22.


## 1-10) Forensic
- From Control Model to Program: Investigating Robotic Aerial Vehicle Accidents with MAYDAY, USENIX security'20.
- RVPLAYER: Robotic Vehicle Forensics by Replay with What-if Reasoning, NDSS'22.


## 1-11) Memory attack detection, recovery, and prevention
- Protecting baremetal embedded systems with privilege overlays, S&P'17.
- Securing real-time microcontroller systems through customized memory view switching, NDSS'18.
- ACES: Automatic compartments for embedded systems, USENIX security'18.


## 1-12) Physical attack detection, recovery, and prevention
- Sensor CON-Fusion: Defeating Kalman Filter in Signal Injection Attack, AsiaCCS'18.
- Detecting Attacks Against Robotic Vehicles: A Control Invariant Approach, CCS'18.
- SAVIOR: Securing Autonomous Vehicles with Robust Physical Invariants, USENIX security'20.
- M2MON: Building an MMIO-based Security Reference Monitor for Unmanned Vehicles, USENIX security'21.
- Replay-based Recovery for Autonomous Robotic Vehicles from Sensor Deception Attacks, arxiv.


## 1-13) Discovering bugs
- RVFuzzer: Finding Input Validation Bugs in Robotic Vehicles through Control-Guided Testing, USENIX Security'19.
- Cyber-Physical Inconsistency Vulnerability Identification for Safety Checks in Robotic Vehicles, CCS'20.
- PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles, NDSS'21.
- Control Parameters Considered Harmful: Detecting Range Specification Bugs in Drone Configuration Modules via Learning-Guided Search, ICSE'22.
- PatchVerif: Discovering Faulty Patches in Robotic Vehicles, USENIX Security'23.


## 1-14) Patching bugs
- PGPATCH: Policy-Guided Logic Bug Patching for Robotic Vehicles, S&P'22.


## 1-15) Privacy
- Privaros: A framework for privacy-compliant delivery drones, CCS'20.



# 2. Research papers related to industrial control system (ICS) :factory:

## 2-1) SoK
- SoK: Attacks on Industrial Control Logic and Formal Verification-Based Defenses, Euro S&P'21

  
## 2-2) Anomaly detection with machine learning-based methods
- Anomaly detection for a water treatment system using unsupervised machine learning, ICDMW'17
- Anomaly Detection in ICS based on Data-history Analysis, EICC'20
- Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering, KDD'21
- Log-Based Anomaly Detection With Robust Feature Extraction and Online Learning, T-IFS 2021
- AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis, IEEE TRANSACTIONS ON MOBILE COMPUTING 2022


## 2-3) Anomaly detection with program analysis
- A trusted safety verifier for process controller code, NDSS'14
- AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis, RAID'21
- SCAPHY: Detecting Modern ICS Attacks by Correlating Behaviors in SCADA and PHYsical, S&P'23

    
## 2-4) Anomaly detection with side channels
- Anomoly Detection for PLC Based on Magnetic Side Channel, EI2'20


## 2-5) Invariant-based (a.k.a. policy-based) methods
- Blocking unsafe behaviors in control systems through static and dynamic policy enforcement, DAC'15
- A systematic framework to generate invariants for anomaly detection in industrial control systems, NDSS'19
- PLC-Sleuth: Detecting and Localizing PLC Intrusions Using Control Invariants, RAID'20
- Control Behavior Integrity for Distributed Cyber-Physical Systems, ICCPS'20
- Detecting and localizing PLC intrusions using control invariants, IEEE Internet of Things Journal, 2022
- Exploiting the Temporal Behavior of State Transitions for Intrusion Detection in ICS/SCADA, IEEE Access 2022
- Anomaly Detection based on Robust Spatial-temporal Modeling for Industrial Control Systems, MASS 2022

  
## 2-6) Formal method
- A Temporal Logic for Programmable Logic Controllers, Automatic Control and Computer Sciences 2021


## 2-7) Discovering and patching bugs and vulnerabilities
- Towards automated safety vetting of PLC code in real-world plants, S&P'19
- Detecting Insecure Code Patterns in Industrial Robot Programs, ASIACCS'20
- ICSFuzz: Manipulating I/Os and Repurposing Binary Code to Enable Instrumented Fuzzing in ICS Control Applications, USENIX Security'21
- Empirical Study of PLC Authentication Protocols in Industrial Control Systems, SPW'21
- Automated Runtime Mitigation for Misconfiguration Vulnerabilities in Industrial Control Systems, RAID'22
- ICSPatch: Automated Vulnerability Localization and Non-Intrusive Hotpatching in Industrial Control Systems using Data Dependence Graphs, USENIX Security'23

  
## 2-8) Attacks 
- Constrained Concealment Attacks against Reconstruction-based Anomaly Detectors in Industrial Control Systems, ACSAC'20


## 2-9) Reverse engineering
- SePanner: Analyzing Semantics of Controller Variables in Industrial Control Systems based on Network Traffic, ACSAC'23


# 3. Research papers related to autonomous vehicles :red_car:
## 3-1) SoK/Survey
- SoK: On the Semantic AI Security in Autonomous Driving, arxiv 2022.

## 3-2) Discovering bugs
- Av-fuzzer: Finding safety violations in autonomous driving systems, ISSRE'20.
- A Comprehensive Study of Autonomous Vehicle Bugs, ICSE'20.
- Plug-N-Pwned: Comprehensive Vulnerability Analysis of OBD-II Dongles as A New Over-the-Air Attack Surface in Automotive IoT, USENIX Security'20.
- Automated Discovery of Denial-of-Service Vulnerabilities in Connected Vehicle Protocols, USENIX Security'21.
- Drivefuzz: Discovering autonomous driving bugs through driving quality-guided fuzzing, CCS'22.
- Too Afraid to Drive: Systematic Discovery of Semantic DoS Vulnerability in Autonomous Driving Planning under Physical-World Attacks, NDSS'22.
- Doppelganger Test Generation for Revealing Bugs in Autonomous Driving Software, ICSE'23.
- Discovering Adversarial Driving Maneuvers against Autonomous Vehicles, USENIX security'23.


## 3-3) Physical attacks
- Drift with Devil: Security of Multi-Sensor Fusion based Localization in High-Level Autonomous Driving under GPS Spoofing, USENIX Security'20.
-  Towards Robust LiDAR-based Perception in Autonomous Driving: General Black-box Adversarial Sensor Attack and Countermeasures, USENIX Security'20.
- Invisible in both Camera and LiDAR: Security of Multi-Sensor Fusion based Perception in Autonomous Driving Under Physical-World Attacks, S&P'21.
- Dirty Road Can Attack: Security of Deep Learning based Automated Lane Centering under Physical-World Adversarial Attack, USENIX Security'21.
- You Can't See Me: Physical Removal Attacks on LiDAR-based Autonomous Vehicles Driving Frameworks, USENIX Security'23.


## 3-4) Preventing or mitigating physical attacks
- Exorcising "Wraith": Protecting LiDAR-based Object Detector in Automated Driving System from Appearing Attacks, USENIX Security'23.


## 3-5) Privacy
- Understand Users' Privacy Perception and Decision of V2X Communication in Connected Autonomous Vehicles, USENIX Security'23.


# 4. Research papers related to satellites :satellite:
## 4-1) Discovering bugs or vulnerabilities
- Space Odyssey: An Experimental Software Security Analysis of Satellites, S&P'23.


## 4-2) Preventing attacks
- Watch This Space: Securing Satellite Communication through Resilient Transmitter Fingerprinting, CCS'23.


# 5. Other research topics related to CPS
## 5-1) Hotpatching
- HERA: Hotpatching of Embedded Real-time Applications, NDSS'21.
- RapidPatch: Firmware Hotpatching for Real-Time Embedded Devices, USENIX Security'22.


## 5-2) Verifying/Testing correctness of CPS
- VeriFast: A powerful, sound, predictable, fast verifier for C and Java, NASA formal methods symposium 2011.
