# CCNA labs

Lab files for the [CCNA topic on yuval.guide](https://www.yuval.guide/ccna/ccna-top/), for the CCNA v2.0 exam (200-301), built in Cisco Packet Tracer 9.0.1.

Each lab is one directory, named like the lesson it belongs to (`1-1-how-data-moves` for section 1.0, lesson 1). The instructions are on the site; a directory holds only the lab's files:

- `*.pkt`: the network, opened in Packet Tracer.
  - It is a binary file, so git cannot show what changed in it.
- `*.txt`: the running configuration of a device, as plain text.
  - git shows every change to it.

To install Packet Tracer and learn its window, follow the [Packet Tracer Guide](https://www.yuval.guide/ccna/packet-tracer-guide/).

## Labs

- [`packet-tracer-guide`](packet-tracer-guide): one 2911 router, one 2960 switch and two PCs, the network the Packet Tracer Guide builds.
