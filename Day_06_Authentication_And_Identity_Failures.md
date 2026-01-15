# Day 6 – Authentication and Identity Failures

## Objective

# 

To understand how authentication and identity systems fail and why identity is one of the most targeted areas in cybersecurity.

* * *

## Why Identity Is a Primary Target

# 

Authentication decides **who you are**.  
Authorization decides **what you can do**.

If identity is compromised, security controls become meaningless.  
Attackers focus on identity because it gives direct access without breaking systems.

* * *

## Common Authentication Mistakes

# 

Frequent failures include:

-   Weak or reused passwords
    
-   No rate limiting on login attempts
    
-   Missing multi-factor authentication
    
-   Poor password storage practices
    
-   Predictable credential patterns
    

These issues allow attackers to gain access using simple methods.

* * *

## Session and Token Weaknesses

# 

After login, systems rely on sessions or tokens.

Failures happen when:

-   Session IDs are predictable
    
-   Tokens are stored insecurely
    
-   Sessions do not expire properly
    
-   Logout does not invalidate sessions
    

Attackers reuse or steal sessions to stay authenticated.

* * *

## Authorization Failures

# 

Authentication alone is not enough.

Authorization fails when:

-   Role checks are missing
    
-   Users can access other users’ data
    
-   Admin functionality is exposed
    
-   Access control is enforced only on the client side
    

This leads to privilege escalation.

* * *

## Identity Trust Across Systems

# 

Modern systems use:

-   Single sign-on
    
-   OAuth
    
-   Third-party identity providers
    

Failures occur when:

-   Tokens are trusted without verification
    
-   Permissions are too broad
    
-   Third-party access is not monitored
    

A weak identity integration can compromise multiple systems.

* * *

## Defense Perspective

# 

To protect identity systems:

-   Enforce strong password policies
    
-   Implement multi-factor authentication
    
-   Apply rate limiting and monitoring
    
-   Secure session and token handling
    
-   Validate authorization on every request
    

Identity security must be strict and consistent.

* * *

## Real-World Relevance

# 

Many breaches happened due to:

-   Credential stuffing attacks
    
-   Stolen session tokens
    
-   Misconfigured access controls
    
-   Over-privileged user accounts
    

Identity compromise is often silent but powerful.

* * *

## Key Learning of Day 6

# 

Identity is the foundation of security.

If authentication or authorization fails, attackers do not need exploits.  
They simply log in.

Strong identity management is essential for secure systems.
