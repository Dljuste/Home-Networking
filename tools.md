# Tools I Used

## 🎥 Tools Overview Video
I recorded a short video showing all the tools I used for this networking lab and explaining why I chose them.

👉 **[Watch the Tools Overview Video](https://youtu.be/CUzPyFMBYMY)**

This video gives a quick walkthrough of the router, switch,Ethernet cables and software I used for the project.

---

## 🧰 Wireshark
I used Wireshark to capture and inspect network packets.  
This helped me learn:
- what DNS, TCP, and HTTPS traffic looks like  
- how to follow streams  
- how encrypted traffic appears when using a VPN or Tor  

---

## 📊 ntopng
I used ntopng to visually monitor traffic.  
It showed me:
- bandwidth usage  
- which protocols were active  
- traffic spikes  
- flow information  

It made it easier to understand what was happening on the network in real time.

---

## 📡 GL-SFT1200 Router
This router let me test:
- normal traffic  
- VPN traffic (WireGuard and OpenVPN)  
- Tor mode traffic  

I used it to see how encrypted traffic changes what you can see in Wireshark and ntopng.

---

## 🔌 TP-Link TL-SG105E Smart Switch
I used the switch to learn about:
- port mirroring (sending traffic to my laptop for capture)  
- VLAN menus (even though I couldn’t fully use them with one device)  
- port status and basic diagnostics  

This helped me understand what managed switches can do in a real network.

---

## 💻 Laptop (Main Testing Device)
My laptop was the only device connected to the switch for this project.  
I used it to:
- run Wireshark  
- run ntopng  
- view traffic coming from the router  
- test VPN and Tor modes  

Since I only had one device, this lab was a simple flat network, but still very useful for learning.
