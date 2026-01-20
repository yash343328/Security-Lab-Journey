# Day 12 – Endpoint Detection and Response (EDR)

## Objective
To understand what Endpoint Detection and Response is, how it differs from traditional antivirus, and why endpoints are critical in modern cybersecurity.

---

## What an Endpoint Is
An **endpoint** is any device that interacts with a network.

Common endpoints include:
- User laptops and desktops  
- Servers  
- Virtual machines  
- Cloud workloads  

> Endpoints are where users work and attackers operate.

---

## Why Endpoints Are Targeted
Attackers target endpoints because:
- Users interact directly with them  
- Credentials are stored or used there  
- Malware executes on endpoints  
- Detection is often weaker than at the network level  

> Compromising one endpoint can lead to wider access.

---

## What EDR Means
**EDR** focuses on:
- Continuous monitoring of endpoint activity  
- Detecting suspicious behavior  
- Recording detailed telemetry  
- Enabling rapid response actions  

> EDR is **behavior-focused**, not signature-focused.

---

## Difference Between Antivirus and EDR
**Traditional Antivirus:**
- Detects known malware  
- Relies on signatures  
- Focuses on prevention  

**EDR:**
- Detects unknown and fileless attacks  
- Analyzes behavior  
- Supports investigation and response  
- Assumes compromise is possible  

---

## EDR Capabilities
Typical EDR features include:
- Process monitoring  
- Command execution tracking  
- File and registry change detection  
- Network connection monitoring  
- Endpoint isolation  

These features provide **deep visibility**.

---

## Response Actions
EDR allows defenders to:
- Isolate infected endpoints  
- Kill malicious processes  
- Quarantine files  
- Collect forensic data  
- Block further execution  

> Response must be fast and controlled.

---

## Detection Challenges
EDR challenges include:
- High volume of endpoint data  
- Distinguishing normal from abnormal behavior  
- False positives  
- Performance impact  

> Proper tuning is essential.

---

## Real-World Relevance
Many advanced attacks were detected because:
- Unusual process behavior was noticed  
- Command execution patterns were suspicious  
- Endpoints were isolated before spread  

> EDR reduces attacker dwell time.

---

## Key Learning of Day 12
- Endpoints are where attacks become real  
- EDR provides **visibility, detection, and response** at the system level  
- EDR is a critical part of modern security operations
