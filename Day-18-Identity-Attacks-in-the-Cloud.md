# Day 18 – Identity Attacks in the Cloud

## Objective
To understand how attackers abuse identities in cloud environments, why identity is the primary attack surface, and how identity-based attacks enable full cloud compromise.

---

## Why Identity Is the New Perimeter
In cloud environments:
- There is no traditional network boundary
- Resources are accessed via identities
- APIs enforce permissions
- Remote access is normal

> If an attacker controls an identity, they control the cloud.

---

## What an Identity Attack Is
An identity attack occurs when attackers:
- Steal cloud credentials
- Abuse overly permissive roles
- Exploit trust relationships
- Use valid access to avoid detection

These attacks often involve **no malware**.

---

## Common Cloud Identity Types
Cloud environments use multiple identities:
- Human users
- Service accounts
- Roles and assumed identities
- API keys and tokens

Every identity is a potential attack path.

---

## Common Identity Attack Techniques
Attackers commonly:
- Steal credentials from code or logs
- Phish cloud users
- Abuse leaked API keys
- Exploit excessive permissions
- Perform privilege escalation
- Use legitimate APIs for malicious actions

> Identity attacks look like normal activity.

---

## Privilege Escalation in the Cloud
Privilege escalation happens when:
- Roles have wildcard permissions
- Trust policies are misconfigured
- Temporary credentials are abused
- Service-to-service access is too broad

Small permissions can lead to **full control**.

---

## Detection Challenges
Identity attacks are hard to detect because:
- Actions use valid credentials
- No exploit or malware is required
- Activity blends with normal usage
- Alerts may be subtle

Detection must focus on **behavior and context**.

---

## Defensive Controls
To defend against identity attacks:
- Enforce least privilege
- Use multi-factor authentication (MFA)
- Rotate and protect credentials
- Monitor identity and API activity
- Review permissions regularly

> Identity security is cloud security.

---

## Incident Response Considerations
When an identity attack is suspected:
- Rotate or revoke credentials immediately
- Review recent API activity
- Audit permissions and trust policies
- Check for persistence via new roles or keys

Speed matters more than certainty.

---

## Real-World Relevance
Many major cloud breaches occurred because:
- API keys were leaked publicly
- Roles had excessive permissions
- Identity activity was not monitored

> Attackers target **permissions**, not servers.

---

## Key Learning of Day 18
- Identity is the primary attack surface in the cloud  
- Identity attacks are stealthy and powerful  
- Strong identity controls and monitoring are essential for cloud defense
