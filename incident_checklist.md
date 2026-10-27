# Operational Incident Response Checklist

## 1. Phishing Triage
- [ ] Extract raw email headers and originating IP address.
- [ ] Analyze embedded URLs in a secure sandbox.
- [ ] Block malicious sender domains at the gateway.

## 2. Malware Containment
- [ ] Network-isolate the infected host immediately via EDR.
- [ ] Capture volatile system memory and logs.
- [ ] Run full antimalware remediation and verify system integrity.
