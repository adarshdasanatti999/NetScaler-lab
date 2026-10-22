
# NetScaler GSLB Lab

## Overview
This folder contains exercises for Global Server Load Balancing
(GSLB), site communication, DNS-based selection, and resilience.

## Objectives
- Understand GSLB sites, services, and virtual servers.
- Study DNS-based global application distribution.
- Understand GSLB service health and effective state.
- Investigate MEP connectivity and synchronization.
- Test site failure and recovery behavior.

## Lab Scenarios
1. Configure two simulated or lab GSLB sites.
2. Configure GSLB services and virtual servers.
3. Validate DNS responses for the GSLB domain.
4. Investigate MEP connectivity between sites.
5. Troubleshoot a GSLB service marked DOWN.
6. Compare service state and effective state.
7. Test site failure and recovery.
8. Review persistence, site selection, and health decisions.
9. Investigate DNS delegation and resolution problems.

## Configuration Areas
- GSLB sites and services
- GSLB virtual servers
- DNS virtual servers and records
- Health monitoring
- MEP communication
- Site selection methods and persistence

## Verification
- show gslb site
- show gslb service
- show gslb vserver
- nslookup <gslb-hostname>
- dig <gslb-hostname>

Confirm syntax against the installed ADC version.

## Troubleshooting Workflow
1. Verify local and remote service health.
2. Validate DNS resolution and delegation.
3. Check site-to-site connectivity and required ports.
4. Review MEP state and relevant logs.
5. Check effective state and selection configuration.
6. Record findings and verify recovery.

## Folder Structure
- configs/
- test-cases/
- troubleshooting/
- evidence/

## Safety
Use lab IP addresses, hostnames, and sanitized outputs only.
