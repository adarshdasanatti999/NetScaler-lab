
# NetScaler SSL/TLS Lab

## Overview
This folder contains personal lab exercises for configuring,
validating, and troubleshooting SSL/TLS on NetScaler ADC.

## Objectives
- Understand SSL/TLS termination and offloading.
- Configure certificates and SSL virtual servers.
- Validate TLS handshakes and certificate chains.
- Troubleshoot certificate, cipher, and protocol issues.
- Understand frontend and backend SSL connections.

## Lab Scenarios
1. Configure an SSL load-balancing virtual server.
2. Install and bind a server certificate and key in the lab.
3. Validate hostname matching and certificate chain.
4. Test TLS connectivity from a client.
5. Investigate certificate trust and expiry errors.
6. Compare frontend TLS and backend HTTP/HTTPS.
7. Examine TLS negotiation using Wireshark.
8. Document SSL profile and protocol compatibility tests.

## Verification Commands
Use appropriate commands for your ADC version.

- show ssl vserver <vserver-name>
- show ssl service <service-name>
- show ssl profile
- openssl s_client -connect <host>:443 -servername <hostname>

## Test Documentation
For each test, record:
- Objective and prerequisites
- Initial configuration
- Steps to reproduce
- Expected and actual results
- Relevant logs and sanitized packet evidence
- Root cause and resolution

## Folder Structure
- configs/       Sanitized configuration examples
- test-cases/    SSL/TLS test procedures
- troubleshooting/ Certificate and handshake issues
- evidence/      Sanitized screenshots and output

## Safety
Never commit private keys, passwords, tokens, or
production/customer certificates and configurations.

## References
- NetScaler product documentation
- OpenSSL documentation
- Relevant TLS RFCs
