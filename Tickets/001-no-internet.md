# Ticket 001: Unable to Access the Internet

## Ticket Information

- Ticket ID: 001
- Category: Network Connectivity
- Priority: Medium
- Status: Investigation Completed
- Environment: Windows 11
- Type: Simulated IT Support Scenario

## User Report

An employee reports that their computer is connected to the Wi-Fi network, but cannot access websites or Internet-based applications.

## Troubleshooting Performed

1. Executed `ipconfig` to inspect network adapters.
2. Executed `ping 8.8.8.8` to test external IPv4 connectivity.
3. Executed `nslookup google.com` to verify DNS resolution.
4. Executed `ping google.com` to test connectivity using a domain name.
5. Executed `ping -4 google.com` to specifically test IPv4 connectivity.
6. Inspected network configuration using `ipconfig`.

## Diagnostic Findings

- Active network adapter: Ethernet.
- IPv4 address: 192.168.1.137.
- Subnet mask: 255.255.255.0.
- IPv4 default gateway: 192.168.1.1.
- Wi-Fi adapters: Disconnected.
- External IPv4 connectivity: Successful.
- IPv6 connectivity: Successful.
- DNS resolution: Successful.
- Packet loss: 0%.

## Diagnosis

The reported connectivity issue could not be reproduced during testing.

The computer had an active Ethernet connection and successfully communicated with external IP addresses and domain names.

The Wi-Fi adapters appeared disconnected, but this did not prevent Internet access through Ethernet.

## Resolution

No corrective action was necessary because connectivity tests were successful.

Further investigation would be required if the original issue occurred again.

## Final Result

Investigation completed. No active Internet connectivity problem was identified.

## Lessons Learned

- Use `ipconfig` to identify active network adapters.
- Use `ping` to test network connectivity.
- Use `nslookup` to investigate DNS resolution.
- Distinguish between Wi-Fi connectivity and Ethernet connectivity.
- Never assume the reported cause is the actual technical cause.
Pending investigation.

## Lessons Learned

To be completed after the exercise.
