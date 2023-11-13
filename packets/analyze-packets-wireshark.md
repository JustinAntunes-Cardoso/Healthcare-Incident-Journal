# Wireshark Packet Analyzer Overview

## Overview

In this lab, the goal was to leverage Wireshark, a network protocol analyzer with a graphical user interface, to analyze network traffic by examining a sample packet capture file. The primary objective was to filter and inspect packet data to identify critical information related to a user's connection to an internet site.

## Activities

### 1. Exploring Data with Wireshark
- Opened a packet capture file to gain an overview of the presented data.
- Understood key property columns for each packet, such as source and destination IP addresses, protocols, and lengths.
- Applied basic filters to focus on specific IP addresses and protocols.
- Identified the protocol of a specific packet.

### 2. Applying Filters and Inspecting a Packet
- Opened a detailed view of a single packet to explore various protocol and data layers.
- Analyzed a Transmission Control Protocol (TCP) packet in detail, including source and destination ports, sequence numbers, and flags.

### 3. Using Filters to Select Packets
- Employed filters to analyze packets based on source and destination IP addresses.
- Applied filters to explore packets related to a specific Ethernet MAC address.
- Identified the protocol contained in the Internet Protocol Version 4 subtree from a filtered packet.

### 4. Exploring DNS Packets
- Used filters to select and examine Domain Name System (DNS) traffic.
- Drilled down into DNS packets to explore queries and answers related to specific websites.

### 5. Exploring TCP Packets
- Applied filters to select and examine Transmission Control Protocol (TCP) packets.
- Searched for text data present in payload data inside network packets.
- Answered questions related to specific TCP packets, including Time to Live, Frame Length, Header Length, and Destination Address.

## Conclusion

In conclusion, this lab provided practical experience in using Wireshark to open and analyze saved packet capture files, view high-level packet data, and employ filters to inspect detailed packet information. This hands-on activity is a significant step in understanding how to leverage network packet analysis tools for examining network traffic in a cybersecurity context.

