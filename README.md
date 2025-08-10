# Multi-Cloud-Security-Audit-Lab
## Overview
A practical audit and hardening project across AWS and Azure focused on identity, network boundaries, and continuous detection so misconfigurations are caught before they turn into incidents.

## Objectives

- Review IAM and network controls against security benchmarks.

- Increase visibility across clouds with native and XDR signals.

- Produce actionable remediation steps mapped to compliance controls.

## Scope

**Clouds:** AWS and Azure

**Services reviewed:** IAM, Security Groups/NSGs, VPC/VNet, Microsoft Defender for Cloud, AWS GuardDuty

**Benchmarks and standards:** CIS guidance, NIST SP 800-53, ISO 27001

## What I did

- Audited policies and network rules across accounts and subscriptions, finding more than 20 permission issues that violated least-privilege guidance from CIS checks.

- Integrated Microsoft Defender XDR with Azure Security Center and enabled AWS GuardDuty to highlight suspicious role usage and privilege escalation attempts.

- Mapped findings to NIST 800-53 and ISO 27001 and delivered remediation steps with evidence, which drove about a 40% reduction in identified compliance gaps in follow-up reviews.

## Representative fixes

- Replace broad “:” IAM actions with scoped permissions and resource conditions.

- Lock down management ports with just-in-time access and private endpoints.

- Enable centralized logging and threat detections with clear alert routing.

## Deliverables

- Concise audit report with a prioritized risk list.

- Control mappings with before/after notes.

- Reusable hardening commands and configuration examples.

## Getting started

- I review AWS IAM policies, Azure role assignments, and network rules for least‑privilege and unnecessary exposure.

- I turn on GuardDuty and Microsoft Defender for Cloud, then review high/medium alerts and tune them to reduce noise.

- I apply the fixes above, reassess, and document before/after results with screenshots and notes.
