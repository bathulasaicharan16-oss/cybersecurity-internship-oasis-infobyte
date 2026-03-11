# Task 8 – Capture Network Traffic with Wireshark

## Objective
The objective of this task is to capture and analyze network traffic using Wireshark to understand how packets travel across a network.

## Tool Used
Wireshark

## Steps Performed
1. Installed Wireshark on Kali Linux.
2. Launched Wireshark and selected the active interface (eth0).
3. Started capturing packets.
4. Generated network traffic by browsing websites.
5. Applied DNS and HTTP filters to analyze packets.
6. Observed packet details such as source IP, destination IP, protocol, and packet size.
7. Saved the captured traffic.

## Packet Analysis
During the packet capture, several protocols were observed including:

- ICMP
- DNS
- TCP
- HTTP

Example packet information:

Source IP: Local machine  
Destination IP: External server  
Protocol: DNS

## Files Included
- wireshark_capture.pcap
- Packet capture screenshots

## Conclusion
Wireshark is a powerful network analysis tool used by cybersecurity professionals to monitor and analyze network traffic. It helps detect suspicious activity and understand communication between systems.
