# netskope-sse-lab

Hands-on lab projects built while studying for a Netskope Cloud Support Engineer role. Each project targets a specific area of the Netskope One SSE platform — traffic inspection, DLP, ZTNA, and cloud app security.

---

## Projects

### Project 1 — Traffic Flow Simulator

Interactive browser-based simulator of the Netskope single-pass inspection pipeline.

**Live demo:** https://dpalm88.github.io/netskope-sse-lab/project-1-traffic-flow/netskope-traffic-flow.html

7-stage pipeline: device → steering → SSL decrypt → single-pass inspect → policy engine → re-encrypt → destination. Configurable: SSL on/off, DLP match, threat detection, steering method, policy action. Packet animates through each stage with real-time inspection log.

---

### Project 2 — DLP Policy + Shadow IT Discovery *(coming soon)*

Live Netskope tenant: client agent, real-time DLP policy, Cloud Confidence Index shadow IT discovery.

---

### Project 3 — ZTNA Private Access Lab *(coming soon)*

Netskope Publisher on AWS EC2, private app tunneled through Netskope. VPN replacement demo.

---

## Background

Prep for Netskope Cloud Support Engineer (FedRAMP/GovCloud). Prior: Snowflake FedRAMP/GovCloud support, OAuth2, NIST 800-53, vSphere, Windows Server, M365. Certs: SnowPro Core, AZ-900, Apple ACMT.

Related: [azure-zero-trust-lab](https://github.com/Dpalm88/azure-zero-trust-lab) | [azure-dr-runbook](https://github.com/Dpalm88/azure-dr-runbook) | [strava-insights](https://github.com/Dpalm88/strava-insights)

## Running Locally

```bash
git clone https://github.com/Dpalm88/netskope-sse-lab.git
open project-1-traffic-flow/netskope-traffic-flow.html
```
