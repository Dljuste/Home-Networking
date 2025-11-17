

## 📌 Overview
This project focuses on building a small, isolated network environment to analyze real-world traffic behavior using a GL-SFT1200 router and a TL-SG105E smart switch. I used my laptop as the primary endpoint for packet capture, monitoring, and testing. The goal was to observe how routing, encrypted tunnels, and traffic patterns behave in a controlled network using tools like Wireshark and ntopng.

Although my hardware limited me to a single client device, this lab still allowed me to explore essential networking concepts such as routing behavior, DHCP, secure tunneling, Tor routing, and real-time traffic analysis.

---

## 🎯 Objectives
- Create an isolated lab environment for safe network testing  
- Monitor traffic flows using ntopng  
- Capture packets and analyze protocols in Wireshark  
- Test secure routing with WireGuard, OpenVPN, and Tor  
- Observe encrypted vs unencrypted traffic behavior  
- Understand switch features like VLANs & Port Mirroring (not fully utilized due to limited endpoints)  
- Troubleshoot connectivity, DHCP behavior, and routing paths  

---

## 🔧 Hardware & Tools Used
- **GL.iNet GL-SFT1200 (OpenWRT-based router)**
- **TP-Link TL-SG105E Smart Switch**
- **Laptop (Linux-Ubuntu) – primary packet analysis device**
- **Wireshark**
- **ntopng**
- **WireGuard**
- **OpenVPN**
- **Tor Routing Mode**
- **Ethernet connection for direct switch testing**

---

## 🎥 YouTube Videos

I also recorded a few YouTube videos that go along with this project.  
These videos explain:

- Why I built this networking lab  
- What tools I used  
- How packet captures look in Wireshark  
- How traffic flows show up in ntopng  

**You can watch my videos here:**  
[YouTube Playlist – Networking Lab](https://www.youtube.com/playlist?list=PL866gqucOoCS6bdTRmS_JXI78goIkXs1N)

---

**More documentation:**  
- [Setup](setup.md)  
- [Tools Used](tools.md)  
- [Results & What I Learned](RESULTS.md)  
- [Screenshots](SCREENSHOTS.md)
