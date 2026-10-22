
# NetScaler Gateway and VPN Lab

## Overview
This folder documents personal lab exercises for NetScaler
Gateway, remote access, ICA Proxy, and authentication.

## Objectives
- Understand Gateway virtual servers and authentication.
- Study ICA Proxy request flows.
- Validate StoreFront and STA communication.
- Troubleshoot certificate and authentication failures.
- Understand client connectivity and session establishment.

## Lab Scenarios
1. Configure a Gateway virtual server in a test environment.
2. Validate authentication and session establishment.
3. Trace the ICA Proxy connection flow.
4. Check StoreFront and STA reachability.
5. Investigate certificate trust and hostname errors.
6. Review browser HAR files for failed requests.
7. Troubleshoot ICA file retrieval and launch failures.
8. Study DTLS behavior where supported and configured.
9. Test authentication policies and timeout behavior.

## Areas to Investigate
- Gateway virtual server and authentication policies
- Session policies and profiles
- StoreFront and STA configuration
- DNS, routing, and firewall connectivity
- TLS certificates and trust chains
- Browser requests and client-side errors

## Verification
- Check Gateway virtual server state.
- Validate StoreFront and STA reachability.
- Review relevant ADC logs.
- Inspect sanitized HAR files and packet captures.
- Correlate client, Gateway, and backend timestamps.

## Folder Structure
- configs/
- test-cases/
- troubleshooting/
- evidence/

## Safety
Never upload session cookies, access tokens, passwords,
private keys, real user identities, or unredacted HAR files.

Use only an authorized lab environment.
