
## 🎥 Setup Walkthrough Video

I recorded a short video explaining how I set up this networking lab, including how the router, switch, and my laptop were connected.  
You can watch it here:

👉 **[Watch the Setup Video](https://youtube.com/shorts/5PhXHgKTk_I?feature=share)**

This video gives a simple visual explanation of the wiring, tools, and basic layout I used for the project.

---

## 🧩 What I Used
- GL-SFT1200 travel router  
- TP-Link TL-SG105E smart switch  
- My laptop (used as the only device for testing and packet capture)  
- Ethernet cable for direct connection  

---

## 🔌 How I Set Everything Up

1. **Laptop → Switch:**  
   I plugged my laptop into the TL-SG105E switch using Ethernet.

2. **Switch → Router:**  
   The switch was connected to my GL-SFT1200 router, which handled internet access and routing.

3. **Laptop as the Analysis/Packet Capture Machine:**  
   My laptop ran Wireshark and ntopng to monitor traffic moving between the router and the switch.

4. **Router Modes:**  
   I turned on different router features like VPN and Tor mode to see how traffic changed.

5. **One-Device Limitation:**  
   Since I only had my laptop, I kept everything as a simple network.  
   I wasn’t able to fully use VLANs or multi-device port mirroring, but I still explored these settings in the switch to understand them.

---
## Network Topology

👉 **[Check out my network diagram](https://miro.com/app/board/uXjVLP2Z4u8=/?share_link_id=710934070818)**



