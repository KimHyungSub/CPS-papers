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
- EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-552-paper.pdf">paper</a>)
- GhostType: The Limits of Using Contactless Electromagnetic Interference to Inject Phantom Keys into Analog Circuits of Keyboards, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-15-paper.pdf">paper</a>)
- Sound of Interference: Electromagnetic Eavesdropping Attack on Digital Microphones Using Pulse Density Modulation, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-onishi.pdf">paper</a>)
  
  
### 1-2-1) Countermeasures against EMI attacks
  - Electromagnetic interference, Electronics Computer Technology, 2011. (EMI filters such as L-C, Pi, T filters)
  - Ghost talk: Mitigating EMI signal injection attacks against analog sensors, S&P'13. (Shielding and differential signaling)
  - Pycra: Physical challenge-response authentication for active sensors under spoofing attacks, CCS'15. (Low-pass filter)
  - Electromagnetic Signal Injection Attacks on Differential Signaling, arXiv, 2022. (Differential signaling)
  - Wireless manipulation of serial communication, AsiaCCS'22. (Twisted pair and coaxial cables)
    
### 1-2-2) Tools
  - <a href="https://www.ansys.com/products/electronics/ansys-hfss" target="_blank">Electromagnetic Field Simulator</a>


## 1-3) mmWave
- DiskSpy: Exploring a Long-Range Covert-Channel Attack via mmWave Sensing of μm-level HDD Vibrations, USENIX Security'25  (<a href="https://www.usenix.org/system/files/usenixsecurity25-xu-weiye.pdf">paper</a>)

  
## 1-4) GPS/GNSS spoofing
- All Your GPS Are Belong To Us: Towards Stealthy Manipulation of Road Navigation Systems, USENIX security'18.
- Crowd-GPS-Sec: Leveraging Crowdsourcing to Detect and Localize GPS Spoofing Attacks, S&P'18.
- Cryptography Is Not Enough: Real-time Location Spoofing of Authenticated GNSS Signals, arxiv.
- SemperFi: Anti-spoofing GPS Receiver for UAVs, NDSS'22.
- Cryptography Is Not Enough: Relay Attacks on Authenticated GNSS Signals, arXiv (2022).
- Galileo-SDR-SIM: An Open-Source Tool for Generating Galileo Satellite Signals, ION GNSS+ 2023.


## 1-5) Radio attacks
- On the Implications of Spoofing and Jamming Aviation Datalink Applications, ACSAC'22 (<a href="https://aanjhan.com/assets/sathaye22_acsac.pdf">paper</a>)
- MakeShift: Security Analysis of Shimano Di2 Wireless Gear Shifting in Bicycles, USENIX Security'24.


## 1-6) Optical flow spoofing
- Controlling UAVs with Sensor Input Spoofing Attacks, WOOT'16.


## 1-7) Sound noise on gyroscope
- Rocking Drones with Intentional Sound Noise on Gyroscopic Sensors, USENIX security'15.
- WALNUT: Waging Doubt on the Integrity of MEMS Accelerometers with Acoustic Injection Attacks, EuroS&P'17.
- SONIC GUN TO SMART DEVICES YOUR DEVICES LOSE CONTROL UNDER ULTRASOUND/SOUND, BlackHat'17.
- Injected and Delivered: Fabricating Implicit Control over Actuation Systems by Spoofing Inertial Sensors, USENIX Security'18.
- Un-Rocking Drones: Foundations of Acoustic Injection Attacks and Recovery Thereof, NDSS'23.
- TimeTravel: Real-time Timing Drift Attack on System Time Using Acoustic Waves, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-liu-jianshuo.pdf">paper</a>)


## 1-8) Depth camera spoofing
- DoubleStar: Long-Range Attack Towards Depth Estimation based Obstacle Avoidance in Autonomous Systems, USENIX security'22.


## 1-9) Laser injection
- Light Commands: Laser-Based Audio Injection Attacks on Voice-Controllable Systems, USENIX security'20.
 

## 1-10) Sensor spoofing simulation
- Poster: Automated Discovery of Sensor Spoofing Attacks on Robotic Vehicles, CCS'22.


## 1-11) RV swarm
- Swarmbug: Debugging Configuration Bugs in Swarm Robotics, FSE'21.
- Vision-based Drone Flocking in Outdoor Environments, IEEE Robotics and Automation Letters'21.
- SWARMFLAWFINDER: Discovering and Exploiting Logic Flaws of Swarm Algorithms, S&P'22.
- Privacy-Preserving Trajectory Matching on Autonomous Unmanned Aerial Vehicles, ACSAC'22.
- SUAVE: An Exemplar for Self-Adaptive Underwater Vehicles, SEAMS'23.
- Self-Adaptive Mechanisms for Misconfigurations in Small Uncrewed Aerial Systems, SEAMS'23.
- SwarmFuzz: Discovering GPS Spoofing Attacks in Drone Swarms, DSN'23.
- Lightweight Privacy-Preserving Proximity Discovery for Remotely-Controlled Drones, ACSAC'23
- Automated Discovery of Semantic Attacks in Multi-Robot Navigation Systems, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-yeke.pdf">paper</a>)

## 1-12) ROS
- PhysFrame: Type Checking Physical Frames of Reference for Robotic Systems, FSE'21.
- RoboFuzz: Fuzzing Robotic Systems over Robot Operating System (ROS) for Finding Correctness Bugs, FSE'22.
- On the (In)Security of Secure ROS2, CCS'22.
- Decentralized Information-Flow Control for ROS2, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-101-paper.pdf">paper</a>)


## 1-13) Forensic
- From Control Model to Program: Investigating Robotic Aerial Vehicle Accidents with MAYDAY, USENIX security'20.
- RVPLAYER: Robotic Vehicle Forensics by Replay with What-if Reasoning, NDSS'22.


## 1-14) Memory attack detection, recovery, and prevention
- Protecting baremetal embedded systems with privilege overlays, S&P'17.
- Securing real-time microcontroller systems through customized memory view switching, NDSS'18.
- ACES: Automatic compartments for embedded systems, USENIX security'18.


## 1-15) Physical attack detection, recovery, and prevention
- Sensor CON-Fusion: Defeating Kalman Filter in Signal Injection Attack, AsiaCCS'18.
- NoisePrint: Attack Detection Using Sensor and Process Noise Fingerprint in Cyber Physical Systems, AsiaCCS'18.
- Detecting Attacks Against Robotic Vehicles: A Control Invariant Approach, CCS'18.
- SAVIOR: Securing Autonomous Vehicles with Robust Physical Invariants, USENIX security'20.
- M2MON: Building an MMIO-based Security Reference Monitor for Unmanned Vehicles, USENIX security'21.
- Replay-based Recovery for Autonomous Robotic Vehicles from Sensor Deception Attacks, arxiv.
- Software Availability Protection in Cyber-Physical Systems, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-li-ao.pdf">paper</a>)


## 1-16) Discovering bugs
- RVFuzzer: Finding Input Validation Bugs in Robotic Vehicles through Control-Guided Testing, USENIX Security'19.
- Cyber-Physical Inconsistency Vulnerability Identification for Safety Checks in Robotic Vehicles, CCS'20.
- PGFUZZ: Policy-Guided Fuzzing for Robotic Vehicles, NDSS'21.
- Control Parameters Considered Harmful: Detecting Range Specification Bugs in Drone Configuration Modules via Learning-Guided Search, ICSE'22.
- PatchVerif: Discovering Faulty Patches in Robotic Vehicles, USENIX Security'23.
- Truman: Constructing Device Behavior Models from OS Drivers to Fuzz Virtual Devices, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-301-paper.pdf">paper</a>)


## 1-17) Patching bugs
- PGPATCH: Policy-Guided Logic Bug Patching for Robotic Vehicles, S&P'22.
- PATCHAGENT: A Practical Program Repair Agent Mimicking Human Expertise, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-yu-zheng.pdf">paper</a>)
- Logs In, Patches Out: Automated Vulnerability Repair via Tree-of-Thought LLM Analysis, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-kim-youngjoon.pdf">paper</a>)
- SoK: Automated Vulnerability Repair: Methods, Tools, and Assessments, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-hu-yiwei.pdf">paper</a>)
- SoK: Towards Effective Automated Vulnerability Repair, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-li-ying.pdf">paper</a>)
- APPATCH: Automated Adaptive Prompting Large Language Models for Real-World Software Vulnerability Patching, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-nong.pdf">paper</a>)
- DISPATCH: Unraveling Security Patches from Entangled Code Changes, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-sun-shiyu.pdf">paper</a>)
- Attacker Control and Bug Prioritization, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-lacombe.pdf">paper</a>)


## 1-18) Privacy
- Privaros: A framework for privacy-compliant delivery drones, CCS'20.


## 1-19) Control theory
- Learning to Fly—a Gym Environment with PyBullet Physics for Reinforcement Learning of Multi-agent Quadcopter Control, IROS'21.


# 2. Research papers related to industrial control system (ICS) :factory:

## 2-1) SoK
- SoK: Attacks on Industrial Control Logic and Formal Verification-Based Defenses, Euro S&P'21

  
## 2-2) Anomaly detection with machine learning-based methods
- Anomaly detection for a water treatment system using unsupervised machine learning, ICDMW'17
- Anomaly Detection in ICS based on Data-history Analysis, EICC'20
- Time Series Anomaly Detection for Cyber-physical Systems via Neural System Identification and Bayesian Filtering, KDD'21
- Log-Based Anomaly Detection With Robust Feature Extraction and Online Learning, T-IFS 2021
- AttkFinder: Discovering Attack Vectors in PLC Programs using Information Flow Analysis, IEEE TRANSACTIONS ON MOBILE COMPUTING 2022
- Attributions for ML-based ICS Anomaly Detection: From Theory to Practice, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-216-paper.pdf">paper</a>)


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
- ICSQuartz: Scan Cycle-Aware and Vendor-Agnostic Fuzzing for Industrial Control Systems, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-795-paper.pdf">paper</a>)

  
## 2-8) Attacks 
- Constrained Concealment Attacks against Reconstruction-based Anomaly Detectors in Industrial Control Systems, ACSAC'20
- PowerRadio: Manipulate Sensor Measurement via Power GND Radiation, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-295-paper.pdf">paper</a>)
- ReThink: Reveal the Threat of Electromagnetic Interference on Power Inverters, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-691-paper.pdf">paper</a>)
- LightAntenna: Characterizing the Limits of Fluorescent Lamp-Induced Electromagnetic Interference, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-2334-paper.pdf">paper</a>)
- EMIRIS: Eavesdropping on Iris Information via Electromagnetic Side Channel, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-200-paper.pdf">paper</a>)


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
- LiDAR Spoofing Meets the New-Gen: Capability Improvements, Broken Assumptions, and New Attack Strategies, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-350-paper.pdf">paper</a>)
- Invisible Reflections: Leveraging Infrared Laser Reflections to Target Traffic Sign Perception, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2024-1053-paper.pdf">paper</a>)
- MadRadar: A Black-Box Physical Layer Attack Framework on mmWave Automotive FMCW Radars, NDSS'24 (<a href="https://www.ndss-symposium.org/wp-content/uploads/ndss2024_f153_paper.pdf">paper</a>)
- PhantomLiDAR: Cross-modality Signal Injection Attacks against LiDAR, NDSS'25.
- GhostShot: Manipulating the Image of CCD Cameras with Electromagnetic Interference, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-2065-paper.pdf">paper</a>)
- On the Realism of LiDAR Spoofing Attacks against Autonomous Driving Vehicle at High Speed and Long Distance, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-628-paper.pdf">paper</a>)
- Revisiting Physical-World Adversarial Attack on Traffic Sign Recognition: A Commercial Systems Perspective, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-s90-paper.pdf">paper</a>)
- L-HAWK: A Controllable Physical Adversarial Patch Against a Long-Distance Target, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-26-paper.pdf">paper</a>)
- The Ghost Navigator: Revisiting the Hidden Vulnerability of Localization in Autonomous Driving, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-zhang-junqi.pdf">paper</a>)
- Invisible but Detected: Physical Adversarial Shadow Attack and Defense on LiDAR Object Detection, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-kobayashi.pdf">paper</a>)
- From Threat to Trust: Exploiting Attention Mechanisms for Attacks and Defenses in Cooperative Perception, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-wang-chenyi.pdf">paper</a>)
- ControlLoc: Physical-World Hijacking Attack on Camera-based Perception in Autonomous Driving, CCS'25.


## 3-4) Preventing or mitigating physical attacks
- Exorcising "Wraith": Protecting LiDAR-based Object Detector in Automated Driving System from Appearing Attacks, USENIX Security'23.
- Interventional Root Cause Analysis of Failures in Multi-Sensor Fusion Perception Systems, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-36-paper.pdf">paper</a>)
- RollingEvidence: Autoregressive Video Evidence via Rolling Shutter Effect, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-qian.pdf">paper</a>)


## 3-5) Forensic
- Interventional Root Cause Analysis of Failures in Multi-Sensor Fusion Perception Systems, NDSS'25.


## 3-6) Privacy
- Understand Users' Privacy Perception and Decision of V2X Communication in Connected Autonomous Vehicles, USENIX Security'23.


## 3-7) Driving with large language models
- LanguageMPC: Large Language Models as Decision Makers for Autonomous Driving, arxiv 2023.
- Empowering Autonomous Driving with Large Language Models: A Safety Perspective, arxiv 2023.


## 3-8) Predicting object classes and bounding boxes
- You only look once: Unified, real-time object detection, arxiv 2015.
- SSD: single shot multibox detector, ECCV 2016.
- End-to-end object detection with transformers, ECCV 2020. 


## 3-9) EV charging
- Current Affairs: A Security Measurement Study of CCS EV Charging Deployments, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-szakaly.pdf">paper</a>)
 
# 4. Research papers related to satellites :satellite:
## 4-1) Discovering bugs or vulnerabilities
- Space Odyssey: An Experimental Software Security Analysis of Satellites, IEEE S&P'23.
- SoK: Space Infrastructures Vulnerabilities, Attacks and Defenses, IEEE S&P'25.

## 4-2) Attacks
- Time-varying Bottleneck Links in LEO Satellite Networks: Identification, Exploits, and Countermeasures, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-109-paper.pdf">paper</a>)
- Starshields for iOS: Navigating the Security Cosmos in Satellite Communication, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-124-paper.pdf">paper</a>)
- Space RadSim: Binary-Agnostic Fault Injection to Evaluate Cosmic Radiation Impact on Exploit Mitigation Techniques in Space, IEEE S&P'25.
- Mind the Location Leakage in LEO Direct-to-Cell Satellite Networks, IEEE S&P'25.

## 4-3) Preventing attacks
- Watch This Space: Securing Satellite Communication through Resilient Transmitter Fingerprinting, CCS'23.

## 4-4) Honeypot
- HoneySat: A Network-based Satellite Honeypot Framework, arxiv, 2025 (<a href="https://arxiv.org/pdf/2505.24008">paper</a>)

# 5. Other research topics related to CPS
## 5-1) Hotpatching
- HERA: Hotpatching of Embedded Real-time Applications, NDSS'21.
- RapidPatch: Firmware Hotpatching for Real-Time Embedded Devices, USENIX Security'22.
- Kintsugi: Secure Hotpatching for Code-Shadowing Real-Time Embedded Systems, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-mackensen.pdf">paper</a>)

## 5-2) Verifying/Testing correctness of CPS
- VeriFast: A powerful, sound, predictable, fast verifier for C and Java, NASA formal methods symposium 2011.
- VulShield: Protecting Vulnerable Code Before Deploying Patches, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-298-paper.pdf">paper</a>)
- Enhancing Security in Third-Party Library Reuse - Comprehensive Detection of 1-day Vulnerability through Code Patch Analysis, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-576-paper.pdf">paper</a>)
- JBomAudit: Assessing the Landscape, Compliance, and Security Implications of Java SBOMs, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-322-paper.pdf">paper</a>)
- Be Careful of What You Embed: Demystifying OLE Vulnerabilities, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-547-paper.pdf">paper</a>)
- From Large to Mammoth: A Comparative Evaluation of Large Language Models in Vulnerability Detection, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-1491-paper.pdf">paper</a>)
- GenHuzz: An Efficient Generative Hardware Fuzzer, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-wu-lichao.pdf">paper</a>)

## 5-3) Adversarial attacks against CPS
- Learning-Based Vulnerability Analysis of Cyber-Physical Systems, ICCPS'22.
- Stealthy attacks formalized as STL formulas for Falsification of CPS Security, HSCC'23
- Vulnerability Analysis for Safe Reinforcement Learning in Cyber-Physical Systems, ICCPS'24.
  
## 5-4) Honeypots
- HoneyDrone: A medium-interaction unmanned aerial vehicle honeypot, NOMS'18.
- Honeyplc: A next-generation honeypot for industrial control systems, CCS'20.
- ICSPOT: A high-interaction honeypot for industrial control systems, ISNCC'22.
- HoneyICS: A high-interaction physics-aware honeynet for industrial control systems, ARES'23.
- Conpot (https://github.com/mushorg/conpot)

## 5-5) Binary analysis
- VeriBin: Adaptive Verification of Patches at the Binary Level, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-359-paper.pdf">paper</a>)
- Beyond Classification: Inferring Function Names in Stripped Binaries via Domain Adapted LLMs, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-797-paper.pdf">paper</a>)
- BinEnhance: An Enhancement Framework Based on External Environment Semantics for Binary Code Search, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-568-paper.pdf">paper</a>)
- Unleashing the Power of Generative Model in Recovering Variable Names from Stripped Binary, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-276-paper.pdf">paper</a>)

## 5-6) WiFi and Bluetooth security
- Off-Path TCP Hijacking in Wi-Fi Networks: A Packet-Size Side Channel Attack, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-305-paper.pdf">paper</a>)
- CHAOS: Exploiting Station Time Synchronization in 802.11 Networks, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-187-paper.pdf">paper</a>)
- Lend Me Your Beam: Privacy Implications of Plaintext Beamforming Feedback in WiFi, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-5-paper.pdf">paper</a>)
- Rediscovering Method Confusion in Proposed Security Fixes for Bluetooth, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-310-paper.pdf">paper</a>)

## 5-7) RUST
- Translating C To Rust: Lessons from a User Study, NDSS'25 (<a href="https://www.ndss-symposium.org/wp-content/uploads/2025-1407-paper.pdf">paper</a>)

## 5-8) Supply chain attacks/Open-source software security
- SoK: A Security Architect's View of Printed Circuit Board Attacks, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-harrison.pdf">paper</a>)
- A Mixed-Methods Study of Open-Source Software Maintainers On Vulnerability Management and Platform Security Features, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-ayala.pdf">paper</a>)
- "Threat modeling is very formal, it's very technical, and also very hard to do correctly": Investigating Threat Modeling Practices in Open-Source Software Projects,  USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-kaur.pdf">paper</a>)
- "I wasn't sure if this is indeed a security risk": Data-driven Understanding of Security Issue Reporting in GitHub Repositories of Open Source npm Packages, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-ghosh.pdf">paper</a>)
- Context Matters: Qualitative Insights into Developers' Approaches and Challenges with Software Composition Analysis, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-lin-elizabeth.pdf">paper</a>)
- Expert Insights into Advanced Persistent Threats: Analysis, Attribution, and Challenges, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-saha.pdf">paper</a>)
- Patching Up: Stakeholder Experiences of Security Updates for Connected Medical Devices, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-kustosch-patching.pdf">paper</a>)
- ChainFuzz: Exploiting Upstream Vulnerabilities in Open-Source Supply Chains, USENIX Security'25 (<a href="https://www.usenix.org/system/files/usenixsecurity25-deng.pdf">paper</a>)
- Unveiling Security Vulnerabilities in Git Large File Storage Protocol, IEEE S&P'25
- Speedrunning the Maze: Meeting Regulatory Patching Deadlines in a Large Enterprise Environment, IEEE S&P'25
- A Deep Dive Into How Open-Source Project Maintainers Review and Resolve Bug Bounty Reports, IEEE S&P'25
- Study Club, Labor Union or Start-Up? Characterizing Teams and Collaboration in the Bug Bounty Ecosystem, IEEE S&P'25
- Codebreaker: Dynamic Extraction Attacks on Code Language Models, IEEE S&P'25
- Make a Feint to the East While Attacking in the West: Blinding LLM-Based Code Auditors with Flashboom Attacks, IEEE S&P'25
