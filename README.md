Wireshark Traffic Analysis
Hands-on packet capture and analysis project using Wireshark to understand core networking protocols at the packet level.
What This Covers
IP/Ethernet basics — Identified host IP/subnet configuration and distinguished broadcast vs. unicast traffic at both the Ethernet (Layer 2) and IP (Layer 3) layers. Built custom Wireshark display filters to isolate traffic by IP and MAC address.
ARP — Captured and decoded an ARP request/reply pair, identifying the EtherType field used to mark a frame as ARP.
ICMP — Captured and decoded ICMP echo request/reply (ping) packets, identifying the IP protocol field used for ICMP.
Traceroute (TTL behavior) — Captured a tracert session and decoded how TTL is incremented to generate ICMP "TTL Exceeded" replies from each router along the path.
TCP/HTTP session — Decoded a full HTTP session end-to-end: the TCP three-way handshake (SYN, SYN-ACK, ACK), initial sequence numbers (absolute and relative), client/server port numbers, and the final acknowledgment numbers during connection teardown.
