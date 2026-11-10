
# SIEM Analysis Laboratory

## 1. Overview

This laboratory demonstrates how to analyze security events using SIEM concepts and identify suspicious activities through log analysis.

## 2. Objectives

- Understand the purpose of SIEM solutions.
- Analyze security logs.
- Identify suspicious authentication attempts.
- Detect potential brute-force attacks.
- Determine appropriate security responses.

## 3. Scenario

A company reports unusual login activity on one of its internal systems.

The security analyst receives several authentication events from the same IP address.

The objective is to investigate the events and determine whether they represent a potential security incident.

## 4. Simulated Security Logs

The following events are fictional and created for this laboratory.

| Timestamp | Source IP | Username | Event |
|---|---|---|---|
| 09:15:01 | 192.168.1.50 | admin | Failed login |
| 09:15:05 | 192.168.1.50 | admin | Failed login |
| 09:15:09 | 192.168.1.50 | admin | Failed login |
| 09:15:13 | 192.168.1.50 | admin | Failed login |
| 09:15:18 | 192.168.1.50 | admin | Successful login |

## 5. Security Analysis

### Observations

- Multiple failed login attempts occurred.
- All attempts originated from the same IP address.
- The same administrator account was targeted.
- A successful login followed the failed attempts.

### Potential Threat

This activity may indicate a brute-force attack or password guessing attempt.

A successful login after repeated failures increases the security risk.

## 6. Risk Assessment

| Element | Analysis |
|---|---|
| Threat | Brute-force attack |
| Vulnerability | Weak or compromised password |
| Asset | Administrator account |
| Impact | Unauthorized system access |
| Risk Level | High |

## 7. Recommended Security Actions

1. Verify whether the successful login was legitimate.
2. Investigate the source IP address.
3. Review additional authentication logs.
4. Disable or protect the compromised account if necessary.
5. Reset the affected password.
6. Enable Multi-Factor Authentication (MFA).
7. Block the suspicious source IP when justified.
8. Document and escalate the incident.

## 8. SIEM Tools

Examples of SIEM platforms:

- Splunk
- Microsoft Sentinel
- IBM QRadar
- Google Security Operations

## 9. Key Findings

The simulated logs show repeated authentication failures followed by a successful login.

This behavior is suspicious and requires further investigation.

SIEM solutions help security analysts correlate events, detect threats and respond to security incidents.

## 10. Conclusion

This laboratory demonstrates the importance of log monitoring, threat detection and incident investigation.

A security analyst must identify suspicious patterns and take appropriate actions to protect organizational assets.

## 11. Skills Demonstrated

- SIEM fundamentals
- Log analysis
- Threat detection
- Brute-force attack identification
- Risk assessment
- Security incident investigation
