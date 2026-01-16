# Day 7 – Logging, Monitoring, and Detection

## Objective
To understand why logging and monitoring are critical for detecting attacks and why many security failures happen due to lack of visibility.

---

## Why Detection Matters
- Prevention cannot stop every attack
- Detection decides how fast an attack is noticed
- A system that is attacked but not detected is already compromised

---

## What Logging Means in Security
Logging is the record of system and user activity.

### Important Events to Log
- Login and logout attempts
- Authentication failures
- Permission changes
- Service start and stop events
- Access to sensitive resources

> Without logs, there is no evidence of what happened.

---

## Common Logging Failures
Logging often fails because:
- Logs are not enabled
- Logs are incomplete
- Logs are overwritten too quickly
- Logs are not reviewed
- No alerts are configured

> An attack may be visible in logs but ignored.

---

## Monitoring and Alerts
Monitoring turns logs into signals.

### Failures Happen When
- No baseline of normal behavior exists
- Alerts are too noisy or too silent
- Critical alerts are ignored
- No one owns the monitoring process

> Detection requires attention, not just tools.

---

## Attacker Behavior and Stealth
Attackers try to:
- Blend in with normal traffic
- Avoid triggering alerts
- Use valid credentials
- Act slowly over time

This makes detection harder without proper monitoring.

---

## Defense Perspective
Effective detection requires:
- Logging security-relevant events
- Centralizing logs
- Defining alert rules
- Monitoring unusual behavior
- Responding quickly to alerts

> Detection is a continuous process.

---

## Real-World Relevance
Many breaches were detected:
- Months after the initial attack
- By third parties
- Through unusual behavior patterns

> Delayed detection increases damage and cost.

---

## Key Learning of Day 7
- You cannot protect what you cannot see
- Logging provides visibility
- Monitoring provides awareness
- Detection enables response
- **Security without detection is incomplete**
