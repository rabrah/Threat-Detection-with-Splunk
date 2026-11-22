Threat Detection & Security Monitoring with Splunk

Blue Team Cybersecurity Portfolio Project

Author: Randy Abrah
Tools: Splunk Enterprise, Sysmon, Windows Event Logs, MITRE ATT&CK

Project Overview

This project focuses on security monitoring and threat detection using Splunk SIEM. The objective is to analyze Windows security logs and Sysmon telemetry to identify suspicious activity, investigate potential threats, and develop detection searches.

The lab explores common security scenarios such as repeated failed login attempts, suspicious PowerShell execution, and unusual process activity.

Objectives

Analyze Windows Event Logs and Sysmon telemetry.

Detect repeated failed login attempts.

Monitor potentially suspicious PowerShell activity.

Investigate process execution events.

Create Splunk searches, dashboards, and alert concepts.

Map detection scenarios to MITRE ATT&CK.

Document findings and security recommendations.

Tools & Technologies

Tool

Purpose

Splunk Enterprise

SIEM, log analysis, searches, dashboards

Sysmon

Endpoint telemetry and process monitoring

Windows Event Logs

Security and authentication events

PowerShell

Monitoring script execution activity

MITRE ATT&CK

Mapping detection scenarios to adversary techniques

Detection Scenarios

1. Failed Login Detection

Event ID: 4625

Purpose: Identify repeated failed authentication attempts.

MITRE ATT&CK: T1110 – Brute Force

2. PowerShell Activity Monitoring

Data Sources: Sysmon process creation and PowerShell logging

Purpose: Review PowerShell execution and investigate potentially suspicious commands.

MITRE ATT&CK: T1059.001 – PowerShell

3. Process Execution Monitoring

Event ID: Sysmon Event ID 1

Purpose: Monitor process execution, executable paths, and parent-child process relationships.

MITRE ATT&CK: T1059 – Command and Scripting Interpreter

Investigation Workflow

Collect Windows and Sysmon telemetry.

Search and filter events in Splunk.

Identify suspicious activity.

Investigate users, systems, processes, and event context.

Map relevant detections to MITRE ATT&CK.

Document findings and recommendations.

Project Evidence

The repository includes a PowerPoint project presentation outlining the lab architecture, detection use cases, Splunk search examples, monitoring concepts, and investigation workflow.

Screenshots, tested detection results, and investigation findings will be added as the lab is implemented and validated.

Skills Demonstrated

SIEM monitoring

Splunk search fundamentals (SPL)

Windows security log analysis

Sysmon telemetry analysis

Threat detection fundamentals

Security investigation

MITRE ATT&CK mapping

Alerting and dashboard concepts

Technical documentation

Disclaimer: This project is for educational and defensive cybersecurity purposes in a controlled lab environmen
