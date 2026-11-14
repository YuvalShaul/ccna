# Lab 1: Capture a Conversation

The network of [Lab 1](https://www.yuval.guide/ccna/1-1-how-data-moves/capture-a-conversation/), the Packet Tracer Guide's network with a second switch and two servers. The instructions are on the site.

| Device | Port | Address | Gateway | Connected to |
| --- | --- | --- | --- | --- |
| R1 | GigabitEthernet0/0 | 192.168.1.1/24 | | SW1 GigabitEthernet0/1 |
| R1 | GigabitEthernet0/1 | 10.0.0.1/24 | | SW2 GigabitEthernet0/1 |
| PC0 | FastEthernet0 | 192.168.1.10/24 | 192.168.1.1 | SW1 FastEthernet0/1 |
| PC1 | FastEthernet0 | 192.168.1.11/24 | 192.168.1.1 | SW1 FastEthernet0/2 |
| Web Server | FastEthernet0 | 10.0.0.80/24 | 10.0.0.1 | SW2 FastEthernet0/1 |
| DNS Server | FastEthernet0 | 10.0.0.53/24 | 10.0.0.1 | SW2 FastEthernet0/2 |

- The PCs use 10.0.0.53 as their DNS server.
- The DNS server holds one A record: `www.ccna.test` is 10.0.0.80.
- The web server serves HTTP.

- `lab1.pkt`: the network.
- `R1.txt`: the router's running configuration.
- `SW1.txt`, `SW2.txt`: the switches' running configurations, unchanged from the defaults.
