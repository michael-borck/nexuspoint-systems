```yaml
---
title: Incident Escalation Procedures
slug: incident-escalation-procedures
category: support
---

# Incident Escalation Procedures
**Document Version:** 2.3  
**Last Updated:** 15 March 2024  
**Next Review:** 15 June 2024  
**Document Owner:** Sam Okoro, Service Desk Team Lead  
**Approved By:** Priya Sharma, Head of Service Delivery

## Overview

This document outlines the standardised escalation procedures for all service desk incidents at NexusPoint Systems. These procedures ensure consistent response times, appropriate resource allocation, and clear communication throughout the incident lifecycle.

**Note:** Following recent security incidents across the WA market, cybersecurity-related incidents now follow enhanced escalation paths as outlined in Section 4.3. This replaces the previous generic escalation model for security events.

## Incident Severity Classifications

### P1 - Critical
**Definition:** Complete service outage or security breach affecting multiple clients or core infrastructure.

**Examples:**
- Primary data centre connectivity failure
- Ransomware or confirmed security breach
- Complete email system failure affecting >50 users
- Core financial system unavailable during business hours

**Response Target:** 15 minutes initial response
**Resolution Target:** 4 hours maximum
**Communication:** Immediate notification to all stakeholders

### P2 - High
**Definition:** Significant service degradation affecting business operations for multiple users.

**Examples:**
- VPN connectivity issues affecting remote workers
- Database performance degradation (>30% slower than baseline)
- Email delays >2 hours
- Secondary system failures with workarounds available

**Response Target:** 30 minutes initial response
**Resolution Target:** 8 hours maximum
**Communication:** Hourly updates during business hours

### P3 - Medium
**Definition:** Service issues affecting individual users or non-critical systems.

**Examples:**
- Single user account lockouts
- Printer connectivity problems
- Software installation requests
- Non-critical application errors

**Response Target:** 2 hours initial response
**Resolution Target:** 24 hours maximum
**Communication:** Initial acknowledgment + resolution notification

### P4 - Low
**Definition:** Minor issues, requests for information, or planned maintenance coordination.

**Examples:**
- Password reset requests
- Software training questions
- Hardware refresh planning
- Documentation updates

**Response Target:** 4 hours initial response
**Resolution Target:** 72 hours maximum
**Communication:** Standard ticket workflow

## Escalation Matrix

### Tier 1 - Service Desk
**Primary Contact:** Sam Okoro (sam.okoro@nexuspoint.com.au, 0432 891 456)
**Backup:** Available 7:30 AM - 6:00 PM AWST

**Responsibilities:**
- Initial incident triage and classification
- P3 and P4 incident resolution
- First-level troubleshooting for P1 and P2 incidents
- Client communication and ticket management
- Documentation in ConnectWise Manage

**Escalation Triggers:**
- Unable to resolve P3/P4 within target timeframes
- P1/P2 incidents requiring specialist knowledge
- Client requests for management involvement
- Security-related incidents (automatic escalation to Marcus Webb)

### Tier 2 - Technical Specialists
**Infrastructure Lead:** Liam Foster (liam.foster@nexuspoint.com.au, 0447 332 189)
**Security Lead:** Marcus Webb (marcus.webb@nexuspoint.com.au, 0421 567 893)

**Responsibilities:**
- P2 incident resolution
- Complex P3 incidents requiring specialist knowledge
- P1 incident support and coordination
- Root cause analysis for recurring issues
- Technical escalation to vendors when required

**Escalation Triggers:**
- P1 incidents not resolved within 2 hours
- P2 incidents requiring vendor involvement
- Multi-client impact scenarios
- Infrastructure or security architecture changes needed

### Tier 3 - Management
**Service Delivery:** Priya Sharma (priya.sharma@nexuspoint.com.au, 0419 224 167)
**Managing Director:** Alex Nguyen (alex.nguyen@nexuspoint.com.au, 0411 889 234)

**Responsibilities:**
- P1 incident oversight and client communication
- SLA breach management
- Vendor relationship management for critical issues
- Client relationship management during major incidents
- Post-incident review coordination

**Escalation Triggers:**
- P1 incidents exceeding 3 hours
- Client escalation to management level
- Potential SLA breach scenarios
- Media or regulatory attention likely
- Commercial impact >$50,000

## Enhanced Security Incident Procedures

### Immediate Response (0-15 minutes)
1. **Service Desk Action:**
   - Log incident in ConnectWise with "SECURITY" prefix
   - Immediately escalate to Marcus Webb
   - Do NOT attempt initial troubleshooting
   - Preserve all logs and evidence

2. **Security Lead Action (Marcus Webb):**
   - Assess threat level and scope
   - Implement immediate containment measures
   - Notify Priya Sharma if multi-client impact suspected
   - Activate security incident response team if required

### Assessment Phase (15-60 minutes)
1. **Threat Classification:**
   - Confirmed breach: Immediate P1 escalation to Alex Nguyen
   - Suspected breach: Maintain P2 with hourly reviews
   - False positive: Downgrade but maintain enhanced monitoring

2. **Containment Actions:**
   - Network isolation procedures (if required)
   - Account lockdown protocols
   - Backup verification and isolation
   - Client notification preparation

### Communication Protocols
- **Internal:** Security Slack channel + email alerts
- **Client:** Hold all communication until security assessment complete
- **External:** Legal and insurance notifications if breach confirmed

## After-Hours Escalation

### Coverage Hours
- **Standard Support:** Monday-Friday, 7:30 AM - 6:00 PM AWST
- **Emergency Support:** 24/7 for P1 incidents only
- **On-Call Rotation:** Weekly rotation between Liam Foster, Marcus Webb, and Priya Sharma

### Emergency Contact Process
1. Client calls main number (08 9321 7890)
2. After-hours message provides emergency mobile: 0400 NEXUS1 (0400 639 871)
3. On-call engineer assesses severity
4. If genuine P1: Full escalation process activated
5. If non-urgent: Logged for next business day

**Note:** Emergency callout fees apply as per client contracts. $350 callout fee + $200/hour minimum 2 hours for non-P1 incidents.

## Communication Templates

### P1 Incident Notification
```
Subject: [P1 INCIDENT] - [Brief Description] - [Client Name]

We are currently investigating a critical issue affecting [systems/services]. 

Initial Impact: [description]
Current Status: [investigation/containment/restoration]
Next Update: [time]

We understand the business impact and have escalated this to our senior technical team. 

[Contact details for updates]
```

### Resolution Notification
```
Subject: [RESOLVED] - [Original incident description]

This incident has been resolved as of [time/date].

Root Cause: [brief explanation]
Resolution: [actions taken]
Preventive Measures: [if applicable]

A detailed post-incident report will be provided within 48 hours for P1 incidents.
```

## SLA Management

### Current Response Targets
- P1: 99.5% within 15 minutes (Target: 100%)
- P2: 98.2% within 30 minutes (Target: 98%)
- P3: 94.7% within 2 hours (Target: 95%)
- P4: 91.3% within 4 hours (Target: 90%)

### SLA Breach Process
1. Automatic notification to Priya Sharma when target 50% elapsed
2. Management involvement when target 80% elapsed
3. Client notification and recovery plan when breach confirmed
4. Post-incident review mandatory for all SLA breaches

## Key Changes Since Last Version

- **Enhanced security escalation paths** added following market security incidents
- **After-hours emergency contact** updated to new mobile service
- **SLA targets** revised upward following Q1 2024 performance review
- **Communication templates** updated for clearer client messaging

## Contact Quick Reference

| Role | Primary | Mobile | Backup |
|------|---------|--------|---------|
| Service Desk | Sam Okoro | 0432 891 456 | Via main number |
| Infrastructure | Liam Foster | 0447 332 189 | Sam Okoro |
| Security | Marcus Webb | 0421 567 893 | Priya Sharma |
| Management | Priya Sharma | 0419 224 167 | Alex Nguyen |

**Emergency After-Hours:** 0400 639 871 (redirects to on-call rotation)

---

*This document is reviewed quarterly or following any major incident. Feedback and suggestions should be directed to Sam Okoro or submitted via the internal wiki.*

*Last major revision: January 2024 (security incident procedures overhaul)*
```