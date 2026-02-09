# Day 21 – Threat Hunting Fundamentals

## Objective
To understand what threat hunting is, why it is necessary even with security tools in place, and how proactive hunting helps uncover hidden threats.

---

## What Threat Hunting Means
Threat hunting is a **proactive security practice** where analysts:
- Actively search for threats
- Look beyond alerts
- Assume attackers may already be present
- Investigate abnormal behavior

> Threat hunting is driven by curiosity, not alerts.

---

## Why Threat Hunting Is Necessary
Security tools:
- Miss sophisticated attacks
- Generate false positives
- Depend on known patterns

Threat hunting helps:
- Find stealthy attackers
- Reduce dwell time
- Validate security controls
- Improve detection logic

> Absence of alerts does not mean absence of threats.

---

## Threat Hunting vs Traditional Monitoring
**Monitoring:**
- Reactive
- Alert-driven
- Rule-based

**Threat Hunting:**
- Proactive
- Hypothesis-driven
- Behavior-focused

Hunting complements monitoring.

---

## Threat Hunting Hypotheses
A hunt usually starts with a hypothesis, such as:
- An attacker is abusing valid credentials
- Malware is using legitimate tools
- Data is being exfiltrated slowly
- Persistence mechanisms exist

Hypotheses guide investigations.

---

## Data Sources for Threat Hunting
Common hunting data includes:
- Endpoint telemetry (EDR)
- Authentication logs
- Network traffic
- DNS queries
- Cloud API logs
- Application logs

More data improves hunting accuracy.

---

## Hunting Techniques
Common techniques include:
- Baseline deviation analysis
- Behavioral analytics
- Timeline reconstruction
- Indicator-free hunting
- MITRE ATT&CK mapping

> Focus on **behavior**, not signatures.

---

## Analyst Mindset
Effective threat hunters:
- Question normal-looking activity
- Understand attacker tradecraft
- Connect weak signals
- Document findings clearly

Threat hunting is both technical and analytical.

---

## Outcomes of Threat Hunting
Successful hunts:
- Detect hidden attackers
- Identify control gaps
- Improve alert rules
- Strengthen defenses

Every hunt makes security better.

---

## Real-World Relevance
Many advanced threats were discovered because:
- Analysts searched without alerts
- Small anomalies were investigated
- Attackers relied on being unnoticed

> Attackers fear hunters more than tools.

---

## Key Learning of Day 21
- Threat hunting is proactive and continuous  
- It assumes compromise is possible  
- Behavior-focused analysis uncovers hidden threats
