```yaml
---
title: Client Onboarding Checklist
slug: client-onboarding-checklist
category: support
---

# Client Onboarding Checklist

**Document Version:** 2.3  
**Last Updated:** 15 March 2024  
**Owner:** Priya Sharma, Head of Service Delivery  
**Review Date:** 30 June 2024

## Overview

This checklist provides the complete step-by-step process for onboarding new managed service clients at NexusPoint Systems. All service delivery team members must follow this process to ensure consistent service quality and compliance with our SLA commitments.

**Note:** Since implementing our security-first initiative in Q4 2023, additional security assessments are now mandatory for all new clients. Allow extra 2-3 days for security evaluation steps.

## Pre-Onboarding Phase

### Contract Finalisation
- [ ] Contract signed and returned by client
- [ ] SOW (Statement of Work) approved by both parties
- [ ] Payment terms confirmed with Tanya Brooks
- [ ] Client added to ConnectWise PSA system
- [ ] Initial project kickoff scheduled within 5 business days

### Team Assignment
- [ ] Primary Service Delivery Manager assigned
- [ ] Technical lead identified (usually Liam Foster for complex deployments)
- [ ] Security assessment owner assigned (Marcus Webb or designated team member)
- [ ] Service Desk contact established (coordinate with Sam Okoro)

## Phase 1: Initial Discovery (Days 1-3)

### Client Information Gathering
- [ ] Complete Client Information Form (see template in SharePoint/Templates/Onboarding)
- [ ] Obtain emergency contact details for after-hours support
- [ ] Document business hours and critical systems
- [ ] Identify key stakeholders and decision makers
- [ ] Collect existing IT documentation (if available)

### Technical Environment Mapping
- [ ] Network topology documentation
- [ ] Server inventory with specifications
- [ ] Application inventory and dependencies
- [ ] Current backup solutions and schedules
- [ ] Internet service provider details and bandwidth
- [ ] Existing security tools and policies

**Required Tools:**
- Network Discovery Pro (license available from IT)
- Microsoft Visio for topology mapping
- Asset tracking spreadsheet template

## Phase 2: Network Audit & Assessment (Days 3-7)

### Infrastructure Audit
- [ ] Conduct comprehensive network scan using approved tools
- [ ] Document all discovered devices and services
- [ ] Identify security vulnerabilities (coordinate with Marcus Webb)
- [ ] Test internet connectivity and bandwidth
- [ ] Assess wireless network configuration
- [ ] Review firewall rules and configurations

### Security Assessment *(New requirement as of January 2024)*
- [ ] Run baseline security scan using SentinelOne tools
- [ ] Document current patch levels across all systems
- [ ] Review user access controls and permissions
- [ ] Assess endpoint protection status
- [ ] Identify potential compliance gaps
- [ ] Complete Security Risk Register (template in security folder)

### Performance Baseline
- [ ] Establish network performance baselines
- [ ] Document current system utilization
- [ ] Identify performance bottlenecks
- [ ] Record current backup completion times
- [ ] Test disaster recovery procedures (if applicable)

## Phase 3: Monitoring Setup (Days 5-10)

### RMM Deployment
- [ ] Install ConnectWise Automate agents on all monitored systems
- [ ] Configure monitoring policies based on client SLA tier
- [ ] Set up automated patch management (coordinate approval windows)
- [ ] Configure backup monitoring and alerting
- [ ] Test remote access connectivity

**Standard Monitoring Policies by SLA Tier:**
- **Gold:** 5-minute intervals, 24x7 monitoring
- **Silver:** 10-minute intervals, business hours priority
- **Bronze:** 15-minute intervals, best effort response

### Alert Configuration
- [ ] Configure critical system alerts
- [ ] Set up disk space monitoring (80% warning, 90% critical)
- [ ] Configure service monitoring for critical applications
- [ ] Set up network device monitoring via SNMP
- [ ] Configure after-hours escalation procedures

### Security Monitoring *(Enhanced since security pivot)*
- [ ] Deploy endpoint detection and response (EDR) tools
- [ ] Configure SIEM integration for enterprise clients
- [ ] Set up vulnerability scanning schedules
- [ ] Configure security event alerting
- [ ] Establish threat intelligence feeds (for Gold tier clients)

## Phase 4: Documentation Creation (Days 8-12)

### Client Knowledge Base
- [ ] Create client-specific folder structure in IT Glue
- [ ] Document network configuration and topology
- [ ] Record all device credentials in password manager
- [ ] Create emergency contact procedures
- [ ] Document business-critical applications and dependencies

### Standard Operating Procedures
- [ ] Backup and recovery procedures
- [ ] User onboarding/offboarding processes
- [ ] Change management procedures
- [ ] Incident escalation matrix
- [ ] Monthly maintenance schedules

### Runbooks
- [ ] Common troubleshooting procedures
- [ ] Vendor contact information and support contracts
- [ ] Software licensing details
- [ ] Hardware warranty information
- [ ] Network configuration backup procedures

## Phase 5: SLA Configuration & Testing (Days 10-14)

### Service Level Agreement Setup
- [ ] Configure response time targets in PSA system
- [ ] Set up SLA reporting dashboards
- [ ] Configure client portal access (if included in service tier)
- [ ] Establish maintenance windows and exclusions
- [ ] Document exception procedures for emergency changes

**Standard SLA Response Times:**
- **Critical (P1):** 2 hours (Gold), 4 hours (Silver), 8 hours (Bronze)
- **High (P2):** 8 hours (Gold), 12 hours (Silver), 24 hours (Bronze)
- **Medium (P3):** 24 hours (Gold), 48 hours (Silver), 72 hours (Bronze)
- **Low (P4):** 72 hours all tiers

### Testing & Validation
- [ ] Test all monitoring alerts and escalations
- [ ] Validate backup systems and restoration procedures
- [ ] Test remote access from multiple locations
- [ ] Verify security tool functionality
- [ ] Conduct end-to-end incident simulation

### Client Training
- [ ] Conduct service desk orientation session
- [ ] Provide client portal training (if applicable)
- [ ] Review incident reporting procedures
- [ ] Distribute emergency contact cards
- [ ] Schedule monthly business review meeting

## Phase 6: Go-Live & Transition (Days 12-16)

### Service Activation
- [ ] Activate 24x7 monitoring coverage
- [ ] Enable automated alerting systems
- [ ] Begin proactive maintenance schedules
- [ ] Activate security monitoring (for applicable tiers)
- [ ] Start SLA clock and reporting

### Handover Activities
- [ ] Conduct formal handover meeting with client
- [ ] Provide "first 30 days" expectations document
- [ ] Schedule 30-day review meeting
- [ ] Complete onboarding checklist review with Priya Sharma
- [ ] Update project status in ConnectWise PSA

### Quality Assurance
- [ ] Internal QA review of documentation completeness
- [ ] Verify all monitoring systems operational
- [ ] Confirm client satisfaction with onboarding process
- [ ] Document lessons learned and process improvements
- [ ] Archive project materials in designated SharePoint folder

## Post-Onboarding Follow-Up

### Week 1 Activities
- [ ] Daily check-ins with client contact
- [ ] Monitor all alert systems for false positives
- [ ] Address any immediate issues or concerns
- [ ] Fine-tune monitoring thresholds as needed

### 30-Day Review
- [ ] Conduct comprehensive service review meeting
- [ ] Analyze SLA performance metrics
- [ ] Gather client feedback on service quality
- [ ] Identify optimization opportunities
- [ ] Plan any additional service enhancements

## Important Notes

- **Security Clients:** Mining and resources sector clients require additional compliance documentation. Consult Marcus Webb for ASIC and ASX requirements.
- **Emergency Escalation:** For after-hours issues during onboarding, contact Sam Okoro (Service Desk) first, then escalate to Priya Sharma if needed.
- **Tool Access:** New team members may need additional software licenses. Submit requests to Jordan Reeves with 48-hour notice.
- **Client Communication:** All client-facing documentation must be reviewed by assigned Service Delivery Manager before distribution.

## Templates & Resources

**SharePoint Locations:**
- Client onboarding templates: `/Teams/ServiceDelivery/Templates/Onboarding/`
- Security assessment tools: `/Teams/Security/Tools/`
- SLA configuration guides: `/Teams/ServiceDelivery/Documentation/SLA/`

**Key Contacts:**
- Technical escalation: Liam Foster (ext. 2847)
- Security questions: Marcus Webb (ext. 2851)
- Billing/contract issues: Tanya Brooks (ext. 2834)
- Process questions: Priya Sharma (ext. 2842)

---

*This document is updated quarterly. Next review scheduled for June 2024. Please submit process improvement suggestions to the Service Delivery team via our Teams channel.*
```