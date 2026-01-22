# Day 14 – Cloud Security Basics

## Objective
To understand why cloud environments require a different security approach and how misconfigurations become the biggest risk in cloud security.

---

## What Cloud Security Means
Cloud security focuses on protecting:
- Cloud infrastructure  
- Applications and services  
- Data stored and processed in the cloud  
- Identities and access controls  

> In the cloud, security is a **shared responsibility** between the provider and the user.

---

## Shared Responsibility Model
**Cloud providers are responsible for:**
- Physical data centers  
- Hardware and underlying infrastructure  
- Core cloud services availability  

**Users are responsible for:**
- Identity and access management  
- Application security  
- Data protection  
- Configuration of cloud resources  

> Most cloud security failures occur on the **user side**.

---

## Why Cloud Environments Are Targeted
Cloud systems are attractive because:
- They are internet-accessible  
- They scale quickly  
- Misconfigurations are common  
- Sensitive data is often stored centrally  

> Attackers look for **exposed cloud services**, not flaws in cloud platforms.

---

## Common Cloud Security Failures
Typical failures include:
- Publicly accessible storage buckets  
- Over-permissive identity roles  
- Exposed management interfaces  
- Hardcoded cloud credentials  
- Unrestricted API access  

These issues often arise from **convenience and speed**.

---

## Identity and Access in the Cloud
Identity is the **core security control** in cloud environments.

Failures happen when:
- Roles have excessive permissions  
- Temporary credentials are not rotated  
- Service-to-service trust is too broad  
- Access policies are not reviewed  

> Compromised identities can lead to **full cloud access**.

---

## Logging and Visibility Challenges
Cloud environments generate large amounts of data.

Visibility issues include:
- Logging not enabled by default  
- Logs spread across multiple services  
- Short log retention periods  
- Lack of alerting  

> Without logs, cloud incidents often go unnoticed.

---

## Defense Perspective
To secure cloud environments:
- Follow **least privilege** for identities  
- Secure storage and network access  
- Enable and actively monitor cloud logs  
- Perform configuration reviews and audits  
- Treat misconfiguration as a vulnerability  

> Cloud security is mostly about **correct setup**.

---

## Real-World Relevance
Many cloud breaches occurred because:
- Storage was publicly accessible  
- Credentials were leaked  
- Permissions were too broad  

These incidents did **not** exploit cloud providers,  
they exploited **cloud usage mistakes**.

---

## Key Learning of Day 14
- The cloud is not insecure by default  
- **Misconfiguration makes it insecure**  
- Strong identity control, visibility, and configuration management  
  are the foundation of cloud security
