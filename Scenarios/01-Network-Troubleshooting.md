# Scenario 01 — Network Troubleshooting

## Problem

A user reports that their Windows computer is connected to the network but cannot access websites or other network resources.

## Toolkit

USB 1 — IT-TOOLKIT

## Troubleshooting Process

1. Confirm the physical Ethernet or Wi-Fi connection.
2. Check the computer's IP configuration.
3. Verify that the system received a valid IP address, subnet mask, gateway, and DNS server.
4. Test the TCP/IP stack using the loopback address.
5. Ping the default gateway.
6. Test connectivity to an external IP address.
7. Test DNS name resolution.
8. Review active connections and routing information.
9. Use Nmap or Wireshark if deeper network investigation is required.
10. Document the findings and resolution.

## Example Commands

```powershell
ipconfig /all
ping 127.0.0.1
ping <default-gateway>
ping 8.8.8.8
nslookup google.com
tracert google.com
netstat -ano
```

## Possible Findings

- Invalid IP configuration
- DHCP failure
- DNS failure
- Gateway unavailable
- Network adapter problem
- Local firewall or service issue
- Upstream network outage

## Skills Demonstrated

- TCP/IP troubleshooting
- DNS troubleshooting
- Windows networking
- Command-line diagnostics
- Structured troubleshooting
