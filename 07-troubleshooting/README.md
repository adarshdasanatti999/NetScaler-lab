
# NetScaler Troubleshooting and RCA Lab

## Overview
This folder is a knowledge base for systematic NetScaler
troubleshooting, evidence collection, and root cause analysis.

## Objectives
- Follow a repeatable troubleshooting methodology.
- Correlate CLI output, logs, and packet captures.
- Identify the difference between symptoms and root causes.
- Document customer-style technical investigations.
- Build reusable troubleshooting guides.

## Troubleshooting Categories
- Load balancing and service health
- SSL/TLS handshake failures
- Content switching and policy evaluation
- Gateway authentication and ICA Proxy
- GSLB and MEP
- HA synchronization and failover
- DNS, routing, TCP, and MTU issues
- Performance and connection problems
- Interface and packet capture analysis

## Standard Investigation Workflow
1. Define the issue and its impact.
2. Record the topology, versions, and timestamps.
3. Identify the affected traffic flow.
4. Collect relevant ADC state, logs, and counters.
5. Capture traffic at appropriate observation points.
6. Compare packets using addresses, ports, flags,
   TCP sequence/acknowledgment numbers, and timestamps.
7. Form and test a root-cause hypothesis.
8. Apply a controlled fix in the lab.
9. Validate recovery and document the outcome.

## Test Case Template
For every issue, record:
- Problem statement
- Environment and prerequisites
- Steps to reproduce
- Expected and actual results
- Commands and evidence
- Root cause
- Resolution and validation
- Lessons learned

## Folder Structure
- test-cases/
- packet-analysis/
- log-analysis/
- rca-reports/
- templates/

## Safety
Sanitize logs, packet captures, IP addresses, hostnames,
cookies, and identifiers before publishing.
Never include customer-confidential evidence.
