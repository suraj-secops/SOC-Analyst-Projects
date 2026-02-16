# Project – Network Traffic Monitoring (SOC Analysis)

## Objective
Analyze network traffic using Wireshark to identify unusual DNS, HTTP, and TLS communication patterns.

## Tools Used
- Wireshark
- GitHub

## Investigation Summary
- Identified most active host: 10.6.13.133
- Observed DNS queries to uncommon footprintdns domains
- HTTP traffic mainly contained normal Windows activity
- TLS Client Hello packets confirmed encrypted communication attempts

## Key Findings
- Suspicious external domains contacted via encrypted channels
- No direct malware file downloads observed over HTTP

## Folder Structure
- Notes/ → Investigation notes
- Screenshots/ → Evidence screenshots
- Report/ → Final analysis report
