# Investigation Notes

## Objective

Review network traffic and identify differences between normal and suspicious communication patterns from a SOC analyst perspective.

## Areas Reviewed

- Source and destination IP addresses
- TCP and UDP traffic
- Common ports and protocols
- DNS activity
- HTTP and HTTPS
- Repeated outbound connections
- Unknown external IP addresses
- Unusual connection behavior
- Basic C2 and beaconing indicators

## Analysis Approach

During the investigation, I reviewed network traffic to understand which systems were communicating, what protocols were being used, and whether the behavior matched expected network activity.

I focused on indicators such as repeated connections, unfamiliar external IP addresses, unusual ports, and abnormal communication patterns.

## Tools Used

- Wireshark
- Linux
- DNS tools
- WHOIS
- Ping
- Traceroute

## Key Lessons

- A single unusual connection does not automatically confirm malicious activity.
- Source and destination context are important during investigation.
- Repeated outbound communication can require further investigation.
- Unknown external IP addresses should be validated before being classified as malicious.
- Network behavior should be reviewed together with protocol, port, timing, and destination information.

## SOC Workflow

1. Identify the suspicious activity.
2. Review source and destination information.
3. Check the protocol and port.
4. Review connection frequency and timing.
5. Validate the destination or domain.
6. Determine whether the activity requires escalation.
7. Document the findings.

## Evidence

Screenshots and additional supporting evidence will be added when available.

## Disclaimer

All activity documented in this project was performed in authorized lab and training environments.
