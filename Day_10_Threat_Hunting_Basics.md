# Day 10 – Threat Hunting Basics

## Objective
To understand what threat hunting is, why it is needed beyond alerts, and how defenders actively search for hidden attackers.

---

## What Threat Hunting Means
Threat hunting is a **proactive security activity**.

Instead of waiting for alerts, defenders:
- Assume compromise is possible
- Search for abnormal behavior
- Investigate patterns and anomalies

Threat hunting is about **asking the right questions**.

---

## Why Alerts Are Not Enough
Automated alerts detect known patterns, but they fail when:
- Attackers use valid credentials
- Malware behaves like normal processes
- Activity stays below alert thresholds
- New attack techniques are used

**Threat hunting fills this gap.**

---

## Threat Hunting Mindset
A threat hunter thinks:
- What would an attacker do next?
- What behavior looks unusual here?
- What should *never* happen in this system?

Hunting focuses on **behavior, not signatures**.

---

## Common Threat Hunting Areas
Threat hunters often investigate:
- Unusual login times or locations
- Abnormal process execution
- Unexpected network connections
- Unauthorized privilege changes
- Persistence mechanisms

Small anomalies can indicate **serious threats**.

---

## Hypothesis-Based Hunting
Threat hunting starts with a **hypothesis**.

**Example:**  
> “If an attacker gained access, they might create persistence.”

The hunter then checks:
- Startup entries
- Scheduled tasks
- Service changes

This structured approach avoids random searching.

---

## Tools Used in Threat Hunting
Threat hunting relies on:
- Logs and telemetry
- Endpoint data
- Network traffic analysis
- SIEM and EDR platforms

Tools support the hunt, but **logic drives it**.

---

## Defense Perspective
Effective threat hunting requires:
- Good logging and visibility
- Knowledge of normal behavior
- Curiosity and analytical thinking
- Documentation of findings

Threat hunting improves detection over time.

---

## Real-World Relevance
Many advanced attacks were discovered because:
- Analysts noticed small irregularities
- Behavior did not match normal patterns
- Hunters investigated without alerts

Proactive hunting reduces **attacker dwell time**.

---

## Key Learning of Day 10
Threat hunting assumes attackers are already inside.

Security improves when defenders stop waiting for alerts and start **actively looking for threats**.
