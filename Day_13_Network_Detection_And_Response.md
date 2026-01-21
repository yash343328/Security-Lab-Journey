# Day 13 – Network Detection and Response (NDR)

## Objective

# 

To understand what Network Detection and Response is, how it complements endpoint security, and why network visibility is critical for detecting attacks.

* * *

## What Network Detection Means

# 

Network Detection focuses on monitoring:

-   Network traffic
    
-   Communication patterns
    
-   Data movement between systems
    

Unlike endpoint tools, NDR observes activity **in transit** rather than on a single machine.

* * *

## Why Network Visibility Matters

# 

Not all systems run agents.  
Not all attacks leave endpoint traces.

Network visibility helps detect:

-   Lateral movement
    
-   Command and control communication
    
-   Data exfiltration
    
-   Suspicious internal traffic
    

Attackers must communicate. The network reveals this.

* * *

## What NDR Means

# 

NDR systems:

-   Capture and analyze network traffic
    
-   Build baselines of normal behavior
    
-   Detect anomalies and threats
    
-   Support investigation and response
    

NDR focuses on behavior and patterns.

* * *

## Difference Between NDR and Traditional Network Security

# 

Traditional network security:

-   Uses firewalls and rules
    
-   Focuses on blocking traffic
    

NDR:

-   Observes allowed traffic
    
-   Detects suspicious behavior inside the network
    
-   Works even when traffic is permitted
    

NDR assumes attackers may already be inside.

* * *

## Common Network Threat Indicators

# 

NDR looks for:

-   Unusual connection patterns
    
-   Unexpected data transfers
    
-   Suspicious DNS activity
    
-   Beaconing behavior
    
-   Abnormal internal traffic flows
    

Small network anomalies can indicate major attacks.

* * *

## Detection Challenges

# 

NDR challenges include:

-   High traffic volume
    
-   Encrypted traffic visibility
    
-   Identifying false positives
    
-   Understanding normal network behavior
    

Context is essential for accurate detection.

* * *

## Response Actions

# 

NDR supports response by:

-   Alerting analysts
    
-   Providing traffic context
    
-   Supporting containment decisions
    
-   Assisting threat hunting
    

Response often involves coordination with endpoint and firewall tools.

* * *

## Real-World Relevance

# 

Many attacks were discovered because:

-   Internal traffic was abnormal
    
-   Systems communicated in unexpected ways
    
-   Data exfiltration patterns were detected
    

Network-based detection exposes hidden activity.

* * *

## Key Learning of Day 13

# 

Endpoints show what happens on a system.  
Networks show how systems communicate.

NDR provides visibility into attacker movement and control that endpoints alone cannot detect.
