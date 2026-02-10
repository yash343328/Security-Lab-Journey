# Day 22 – MITRE ATT&CK Framework

## Objective
To understand what the MITRE ATT&CK framework is, why it is important in cybersecurity, and how defenders use it to analyze, detect, and respond to real-world attacks.

---

## What MITRE ATT&CK Is
MITRE ATT&CK is a **knowledge base of adversary behavior**.

It documents:
- How attackers operate
- Common tactics and techniques
- Real-world attack patterns
- Post-compromise activity

> ATT&CK focuses on **what attackers do**, not what tools they use.

---

## Structure of the ATT&CK Framework
ATT&CK is organized into:

### Tactics
High-level attacker goals, such as:
- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Defense Evasion
- Credential Access
- Lateral Movement
- Command and Control
- Exfiltration
- Impact

Tactics answer **why** an action is performed.

---

### Techniques and Sub-Techniques
Techniques describe **how** attackers achieve a tactic.

Examples:
- Phishing
- Credential Dumping
- Scheduled Task Creation
- Valid Accounts
- Exfiltration Over Web Services

Sub-techniques provide deeper detail.

---

## Why ATT&CK Is Valuable
ATT&CK helps defenders:
- Understand attacker behavior
- Map detections to real techniques
- Identify visibility gaps
- Improve incident response
- Structure threat hunting

It creates a **common language** for security teams.

---

## ATT&CK vs Traditional Indicators
Traditional detection relies on:
- IP addresses
- File hashes
- Signatures

ATT&CK focuses on:
- Behavior
- Tactics and techniques
- Long-term patterns

> Indicators expire. Behavior persists.

---

## How Security Teams Use ATT&CK
Teams use ATT&CK to:
- Design detection rules
- Prioritize logging and monitoring
- Build threat hunting hypotheses
- Assess security maturity
- Guide red and blue team exercises

ATT&CK bridges offense and defense.

---

## ATT&CK in Incident Response
During incidents, ATT&CK helps:
- Classify attacker actions
- Build attack timelines
- Predict next attacker steps
- Communicate clearly with stakeholders

Frameworks reduce chaos during response.

---

## Cloud and ATT&CK
MITRE ATT&CK includes:
- Enterprise techniques
- Cloud-specific techniques
- Identity-based attacks

ATT&CK applies across:
- On-prem environments
- Cloud infrastructure
- Hybrid systems

---

## Real-World Relevance
Most modern security tools:
- Map alerts to ATT&CK techniques
- Use ATT&CK for reporting
- Align detections with attacker behavior

> ATT&CK is the blueprint of modern cyber attacks.

---

## Key Learning of Day 22
- MITRE ATT&CK models real attacker behavior  
- It helps defenders think like attackers  
- Behavior-based frameworks enable stronger detection and response
