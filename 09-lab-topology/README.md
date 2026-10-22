
# NetScaler Lab Topology and Environment

## Overview
This folder documents the design, components, addressing,
and traffic flows of my personal NetScaler lab environment.

## Objectives
- Maintain an understandable lab network diagram.
- Document ADC interfaces and network segments.
- Record client, ADC, and backend communication paths.
- Support repeatable troubleshooting and test execution.
- Track lab changes over time.

## Lab Components
Document the components actually deployed, such as:
- NetScaler ADC VPX
- VMware or EVE-NG
- Ubuntu client or test server
- Windows Server or directory services
- Backend web applications
- DNS and authentication services
- Virtual switches and lab networks

## Documentation to Maintain
1. High-level topology diagram.
2. Logical traffic flow diagrams.
3. Lab IP address plan using safe documentation values.
4. Interface and VLAN mapping.
5. Routing and gateway information.
6. DNS names and test application mapping.
7. Software versions and dependencies.
8. Test prerequisites and known limitations.

## Suggested Diagrams
- Client to ADC to backend traffic flow
- SSL offloading traffic flow
- Content switching across multiple applications
- Gateway authentication flow
- GSLB site selection
- HA pair and synchronization links

## Change Log
Record significant lab changes, including:
- Date
- Change description
- Reason for change
- Expected impact
- Validation performed
- Rollback notes

## Folder Structure
- diagrams/
- addressing/
- traffic-flows/
- inventory/
- change-log/

## Safety
Do not publish real credentials, private keys, sensitive
management addresses, or confidential production topology.
Use sanitized examples and lab-only details.
