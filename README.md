# 🔊 Loud SOC HoneyPot Lab

## Overview
# Loud SOC HoneyPot Lab

This repository documents the deployment of a small-scale SOC lab in Azure focused on attracting and analyzing real-world attack activity.

A deliberately exposed Windows virtual machine was deployed as a honeypot to generate malicious authentication attempts. Windows security events were forwarded to a Log Analytics Workspace and ingested into Microsoft Sentinel, where failed logon activity was investigated using KQL.

To add context to the raw telemetry, IP-based geolocation data was integrated, allowing attacker activity to be enriched and visualized. The lab concludes with the creation of an attack map to better understand attack origin and patterns.

The goal of this project was to practice core SOC analyst workflows: log collection, investigation, enrichment, and visualization, using tools commonly found in enterprise security environments.

## Results & Findings
- Observed real-world brute force attempts
- Identified attacker source countries via GeoIP
- Visualized attack patterns using Sentinel Workbooks

## Lessons Learned
- Importance of centralized logging
- Value of enrichment for threat context
- KQL as a core SOC skill
