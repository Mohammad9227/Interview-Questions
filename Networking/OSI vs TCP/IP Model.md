   OSI Model                  TCP/IP Model           Example Protocols
 ┌──────────────┐         ┌──────────────┐        ┌────────────────────┐
 │ 7. Application│◄──────►│ 4. Application│◄─────►│ HTTP, DNS, FTP      │
 ├──────────────┤         ├──────────────┤        ├────────────────────┤
 │ 6. Presentation│       │              │        │ SSL/TLS, JPEG       │
 ├──────────────┤         │              │        ├────────────────────┤
 │ 5. Session    │        │              │        │ NetBIOS, RPC        │
 ├──────────────┤         ├──────────────┤        ├────────────────────┤
 │ 4. Transport  │◄──────►│ 3. Transport  │◄─────►│ TCP, UDP            │
 ├──────────────┤         ├──────────────┤        ├────────────────────┤
 │ 3. Network    │◄──────►│ 2. Internet   │◄─────►│ IP, ICMP, ARP       │
 ├──────────────┤         ├──────────────┤        ├────────────────────┤
 │ 2. Data Link  │◄──────►│ 1. Network Access│◄──►│ Ethernet, Wi-Fi     │
 ├──────────────┤         ├──────────────┤        ├────────────────────┤
 │ 1. Physical   │        │              │        │ Cables, Radio       │
 └──────────────┘         └──────────────┘        └────────────────────┘

🔹 Notes:
Transport Layer (Layer 4) is where TCP and UDP live.
OSI Model is more detailed (7 layers), while TCP/IP Model is more practical (4 layers).
In practice, the Application Layer in TCP/IP combines OSI Layers 5–7.
