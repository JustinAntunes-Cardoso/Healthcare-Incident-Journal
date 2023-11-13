# Tcpdump Packets Capture Overview

## Overview

Security analysts are tasked with capturing and analyzing network traffic in a Linux environment using `tcpdump`. The focus was on identifying network interfaces, filtering live network traffic, capturing data into a packet capture (pcap) file, and finally examining the captured packet data.

## Activities

### 1. Identify Network Interfaces

- Used `ifconfig` to identify available network interfaces.
- Employed `tcpdump -D` to identify interface options available for packet capture.
- Selected `eth0` as the interface for capturing network packet data.

### 2. Inspect Network Traffic with tcpdump

- Filtered live network packet data from `eth0` using `sudo tcpdump -i eth0 -v -c5`.
- Examined the detailed packet information provided by tcpdump.

### 3. Capture Network Traffic with tcpdump

- Captured network traffic with a filter for port 80 into a file named `capture.pcap`.
- Used `curl` to generate HTTP (port 80) traffic for capturing.
- Verified the captured packet data using `ls -l capture.pcap`.

### 4. Filter Captured Packet Data

- Used `sudo tcpdump -nn -r capture.pcap -v` to filter packet header data.
- Used `sudo tcpdump -nn -r capture.pcap -X` to filter extended packet data in hexadecimal and ASCII formats.

## Conclusion

The security analysts gained practical experience in identifying network interfaces, capturing and filtering network data using `tcpdump`, interpreting packet information, and saving and loading packet data for analysis. This lab provided essential skills for security analysts in capturing network packets effectively.
