# Day 3 – Network as an Attack Surface

## Objective

To understand how computer networks become an entry point for attackers and why network exposure increases security risk.

* * *

## What an Attack Surface Means

An attack surface is the total number of points where an attacker can interact with a system.

In networking, this includes:

-   Open ports
    
-   Running services
    
-   Network protocols
    
-   IP addresses
    
-   Internal and external connections
    

The larger the attack surface, the higher the risk.

* * *

## Why Networks Are Targeted

Networks connect systems together.  
If one system is exposed, others may be affected.

Attackers target networks because:

-   Services are often publicly reachable
    
-   Misconfigurations are common
    
-   Network traffic is trusted by default
    
-   Internal networks are assumed to be safe
    

* * *

## Common Network Entry Points

Typical entry points include:

-   Open ports with vulnerable services
    
-   Unused services still running
    
-   Weakly protected remote access (SSH, RDP)
    
-   Misconfigured firewalls
    
-   Public-facing APIs
    

Attackers scan networks to find these points automatically.

* * *

## Internal Network Trust Problem

Many organizations trust internal network traffic.

This leads to:

-   Lack of authentication inside the network
    
-   Minimal monitoring of internal traffic
    
-   Easy lateral movement after initial access
    

Once inside, attackers move quietly between systems.

* * *

## Network Protocol Weaknesses

Some protocols were not designed with security in mind.

Examples:

-   Plain text communication
    
-   Weak or no authentication
    
-   Susceptibility to spoofing or replay
    

Without encryption and validation, data can be intercepted or modified.

* * *

## Defense Perspective

To reduce network attack surface:

-   Close unused ports and services
    
-   Apply firewall rules strictly
    
-   Segment networks
    
-   Encrypt network communication
    
-   Monitor network traffic continuously
    

Defense is about limiting exposure and visibility.

* * *

## Real-World Relevance

Many attacks begin with:

-   An exposed port discovered through scanning
    
-   A forgotten service running on a server
    
-   A weakly secured remote login service
    

Once access is gained, attackers expand their control through the network.

* * *

## Key Learning of Day 3

A network is not just a communication medium.  
It is a **security boundary**.

Every exposed service increases risk.  
Reducing and monitoring the network attack surface is essential for system security.
