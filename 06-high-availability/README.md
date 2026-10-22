
# NetScaler High Availability Lab

## Overview
This folder documents NetScaler ADC HA configuration,
synchronization, failover, and recovery tests.

## Objectives
- Understand primary and secondary ADC nodes.
- Validate HA configuration and synchronization.
- Investigate heartbeat and communication problems.
- Observe failover and application recovery.
- Understand configuration consistency between nodes.

## Lab Scenarios
1. Configure an HA pair in an isolated lab.
2. Verify primary and secondary node states.
3. Check HA synchronization and configuration propagation.
4. Test controlled failover during a maintenance exercise.
5. Validate application access after failover.
6. Investigate a secondary node that is not UP.
7. Troubleshoot configuration synchronization failures.
8. Review heartbeat and interface connectivity.
9. Document failback and post-test verification.

## Configuration Areas
- HA node configuration
- NSIP and interface connectivity
- HA synchronization
- Heartbeat communication
- Configuration consistency
- Failover and recovery behavior

## Verification
- show ha node
- show ha status
- show ns runningConfig

Check the command syntax and available output on your ADC version.
Do not assume that running configuration and saved configuration
are identical.

## Troubleshooting Workflow
1. Check the state of both nodes.
2. Verify node communication and relevant interfaces.
3. Review synchronization status and system logs.
4. Compare relevant configuration sections.
5. Identify the cause before attempting corrective action.
6. Revalidate application health after recovery.

## Folder Structure
- configs/
- test-cases/
- troubleshooting/
- evidence/

## Safety
Perform failover testing only in a controlled lab.
Keep secure backups before making HA changes.
