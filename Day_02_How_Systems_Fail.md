# Day 2 – How Systems Fail

## Objective

# 

To understand why systems fail from a security point of view and how small design and configuration mistakes turn into serious vulnerabilities.

* * *

## What System Failure Means in Security

# 

In cybersecurity, system failure does not always mean a crash.

A system has failed if:

-   Unauthorized access is possible
    
-   Data can be leaked or modified
    
-   Actions cannot be traced
    
-   Security controls can be bypassed
    

A working system can still be an insecure system.

* * *

## Common Reasons Systems Fail

# 

Most systems fail due to human and design errors, not technical limitations.

The most common causes are:

-   Poor security design
    
-   Misconfiguration
    
-   Over-permission
    
-   Lack of monitoring
    
-   Blind trust in users or services
    

* * *

## Configuration Failures

# 

Configuration is one of the biggest security weaknesses.

Examples:

-   Default passwords left unchanged
    
-   Debug mode enabled in production
    
-   Open ports not required by the application
    
-   Public access to internal services
    
-   Incorrect file and folder permissions
    

These issues are often ignored because the system “works”.

* * *

## Permission and Access Failures

# 

Giving more access than required leads to failure.

Examples:

-   Users having admin privileges without need
    
-   Services running as root
    
-   Shared credentials across systems
    
-   No separation between user roles
    

If one account is compromised, the entire system is at risk.

* * *

## Visibility and Logging Failures

# 

A system without logs is blind.

Failures include:

-   No logging of login attempts
    
-   Logs not monitored or reviewed
    
-   Logs stored insecurely
    
-   Alerts not configured
    

If an attack happens and there is no record, response becomes impossible.

* * *

## Attacker Advantage in System Failure

# 

Attackers take advantage of:

-   Forgotten services
    
-   Old configurations
    
-   Inconsistent security rules
    
-   Lack of monitoring
    

They move slowly and quietly to avoid detection.

* * *

## Defense Perspective

# 

To reduce system failure:

-   Use secure-by-default configurations
    
-   Follow the principle of least privilege
    
-   Regularly audit permissions and services
    
-   Enable and monitor logs
    
-   Treat misconfiguration as a vulnerability
    

Prevention is easier than incident response.

* * *

## Real-World Relevance

# 

Many real-world breaches occurred because:

-   A database was publicly accessible
    
-   An internal service was exposed
    
-   Logs were ignored for months
    

These failures were preventable.

* * *

## Key Learning of Day 2

# 

Systems usually fail because security is treated as optional.

A secure system is not only about strong defenses, but about **correct configuration, controlled access, and visibility**.
