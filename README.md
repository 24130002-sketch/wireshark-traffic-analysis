# Wireshark Traffic Analysis

## Overview
This project demonstrates network traffic capture and analysis using Wireshark, 
performed as part of my cybersecurity learning and coursework.

## Tools Used
- Wireshark
- Kali Linux (Virtual Machine)

## What I Did
- Captured live network traffic on a test network
- Analyzed packet headers to identify protocols (TCP, UDP, HTTP, DNS)
- Used filters to isolate specific traffic types for closer inspection
- Identified normal vs suspicious traffic patterns
- Reviewed packet details including source/destination IPs and ports

## Sample Filters Used
http
dns
tcp.port == 80
ip.addr == 192.168.1.10

## Key Learnings
- Understanding how data flows across a network at the packet level
- Reading and interpreting protocol headers
- Using filters to narrow down large amounts of captured traffic
- Recognizing patterns that could indicate unusual network activity

## Disclaimer
All packet captures were performed on my own network or lab environment for educational purposes only.
