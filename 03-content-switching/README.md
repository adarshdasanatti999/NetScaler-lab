
# NetScaler Content Switching Lab

## Overview
This folder contains lab exercises for routing client requests
to backend applications using NetScaler Content Switching (CS).

## Objectives
- Understand CS virtual servers, policies, and actions.
- Route traffic based on hostname, URL, and HTTP attributes.
- Understand the relationship between CS and LB virtual servers.
- Troubleshoot policy evaluation and incorrect routing.

## Lab Scenarios
1. Route two hostnames to different backend applications.
2. Route requests based on URL paths.
3. Test policy priorities and binding points.
4. Validate CS-to-LB virtual server connections.
5. Investigate default-target behavior.
6. Troubleshoot incorrect policy expressions.
7. Validate HTTP and HTTPS content switching.
8. Test behavior when a backend application is unavailable.

## Configuration Areas
- CS virtual servers
- CS policies and actions
- Policy expressions
- LB virtual servers
- SSL bindings where applicable
- Service groups and monitors

## Verification
- show cs vserver
- show cs policy
- show cs action
- show lb vserver
- Inspect HTTP Host headers and request URLs.
- Confirm the selected backend using lab logs or captures.

Use commands supported by your installed ADC version.

## Test Documentation
Record the request hostname, URL path, matching policy,
selected target, expected result, actual result, and resolution.

## Folder Structure
- configs/
- test-cases/
- troubleshooting/
- evidence/

## Safety
Use lab hostnames and sanitized configurations.
Do not publish customer URLs, credentials, or sensitive headers.
