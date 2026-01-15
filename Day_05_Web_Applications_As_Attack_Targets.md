# Day 5 – Web Applications as Attack Targets

## Objective

# 

To understand why web applications are a primary target for attackers and how design and logic flaws lead to security breaches.

* * *

## Why Web Applications Are Targeted

# 

Web applications are:

-   Publicly accessible
    
-   Used by many users
    
-   Directly connected to databases
    
-   Often developed quickly with less security focus
    

Attackers target web applications because they are exposed and handle sensitive data.

* * *

## Trust Issues in Web Applications

# 

Web applications trust:

-   User input
    
-   Client-side validation
    
-   Cookies and session tokens
    
-   Request headers
    
-   Application logic
    

Attackers exploit this trust by sending unexpected or malicious input.

* * *

## Common Web Application Weaknesses

# 

Typical weaknesses include:

-   Improper input validation
    
-   Broken authentication
    
-   Weak session management
    
-   Excessive error messages
    
-   Insecure direct object access
    

These weaknesses allow attackers to bypass controls without breaking the system.

* * *

## Logic-Based Attacks

# 

Not all attacks use technical exploits.

Logic flaws occur when:

-   Business rules are not enforced properly
    
-   Users can access resources out of order
    
-   Authorization checks are missing
    
-   Client-side restrictions are trusted
    

Attackers manipulate application flow instead of code.

* * *

## Backend and Database Exposure

# 

Web applications often connect directly to databases.

Failures happen when:

-   Queries are built using user input
    
-   Database credentials are exposed
    
-   Error messages reveal internal structure
    
-   Access controls are weak
    

Once backend access is gained, data compromise becomes possible.

* * *

## Defense Perspective

# 

To secure web applications:

-   Validate and sanitize all input
    
-   Enforce authentication and authorization on the server
    
-   Use secure session management
    
-   Hide internal errors from users
    
-   Apply security testing during development
    

Web security must be part of application design.

* * *

## Real-World Relevance

# 

Many major breaches started with:

-   A vulnerable login page
    
-   An exposed admin panel
    
-   A simple input validation flaw
    
-   A missing authorization check
    

Web applications are often the first point of compromise.

* * *

## Key Learning of Day 5

# 

Web applications fail when they trust users too much.

Security in web applications is about:

-   Controlling input
    
-   Enforcing logic
    
-   Protecting backend systems
    

A single web flaw can expose an entire system.
