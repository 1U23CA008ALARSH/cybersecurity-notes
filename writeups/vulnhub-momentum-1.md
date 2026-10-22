# VulnHub Momentum: 1 — Web Security Lab Notes

## Lab Overview
- **Platform:** VulnHub
- **Lab:** Momentum: 1
- **Objective:** Practice web enumeration and vulnerability analysis.
- **Tools:** Kali Linux, Nmap, WhatWeb, Gobuster, browser developer tools.

## Methodology
1. Identified the target machine in my isolated lab environment.
2. Scanned open ports and services using Nmap.
3. Enumerated web directories using Gobuster.
4. Examined the website and its JavaScript source code.
5. Investigated client-side cookie encryption and hardcoded encryption secrets.

## Security Observation
Hardcoding encryption passphrases in client-side JavaScript can expose secrets to anyone who can inspect the source code. If protected cookie data relies on this secret, it may be possible to decrypt or manipulate the data, depending on the implementation and server-side validation.

## Impact
Potential exposure or manipulation of cookie data. Authentication compromise was not confirmed.

## Lessons Learned
- Never store encryption secrets in client-side code.
- Validate authentication and authorization on the server.
- Configure cookies securely.
- Document findings and verify their impact before reporting a vulnerability.

## Lab Reference
https://www.vulnhub.com/entry/momentum-1,685/

**Disclaimer:** This was a controlled educational lab. Findings and impacts should be verified before being reported as confirmed vulnerabilities.
