# Day 11 – SIEM and Log Correlation

## Objective
To understand what SIEM is, why log correlation is important, and how security teams connect events to detect real attacks.

---

## What SIEM Means
**SIEM** stands for **Security Information and Event Management**.

A SIEM system:
- Collects logs from multiple sources  
- Stores them centrally  
- Analyzes events  
- Generates alerts  
- Supports investigations  

> **SIEM does not create security.  
It makes security visible.**

---

## Why Centralized Logs Matter
Individual logs show only small pieces of activity.

Centralized logging allows:
- Correlation across systems  
- Timeline reconstruction  
- Pattern identification  
- Faster investigations  

> Attacks are rarely visible in a single log.

---

## What Log Correlation Means
**Log correlation** connects related events across different systems.

**Example attack sequence:**
- Failed login attempts  
- Followed by a successful login  
- From a new location  
- Followed by privilege escalation  

Individually, events may look normal.  
**Together, they indicate an attack.**

---

## Common Data Sources in SIEM
SIEM typically collects logs from:
- Authentication systems  
- Servers and endpoints  
- Network devices  
- Firewalls and proxies  
- Applications and databases  

> More context improves detection accuracy.

---

## Common Correlation Failures
SIEM fails when:
- Important logs are missing  
- Time synchronization is incorrect  
- Correlation rules are weak  
- Too many false positives exist  
- Alerts are not reviewed  

> A poorly tuned SIEM creates noise.

---

## Analyst Perspective
A security analyst uses SIEM to:
- Investigate alerts  
- Build timelines  
- Validate incidents  
- Support threat hunting  
- Improve detection rules  

> SIEM is a **decision-support system**, not an automatic solution.

---

## Defense Perspective
Effective SIEM usage requires:
- Clear logging standards  
- Relevant correlation rules  
- Regular tuning  
- Analyst involvement  
- Continuous improvement  

SIEM effectiveness grows over time.

---

## Real-World Relevance
Many breaches were detected because:
- Multiple small events were correlated  
- Analysts connected unrelated logs  
- Suspicious patterns emerged  

> Correlation turns data into intelligence.

---

## Key Learning of Day 11
- Logs alone are **data**  
- Correlation turns data into **insight**  
- SIEM helps defenders see the **full picture**, not isolated events
