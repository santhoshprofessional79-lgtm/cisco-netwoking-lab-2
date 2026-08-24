 🚀 SOC Analyst Network Foundations: Lab 2


 🛠️ Tools Used
* Cisco Packet Tracer
* Network Simulation Mode (for Packet/PDU analysis)

---

🔬 Lab 1: Layer 2 & Layer 3 Connectivity (ARP & ICMP)
**Objective:** Understand the baseline interaction between MAC Addresses (Layer 2) and IP Addresses (Layer 3) before a successful ICMP Ping can occur.

 📝 Key Operations Analyzed:
1. **ARP Broadcast:** Observed how a PC sends an `FF:FF:FF:FF:FF:FF` broadcast to resolve an unknown destination MAC address on the local network.
2. **Switch MAC Learning:** Analyzed how the switch populates its MAC Address Table dynamically upon receiving the initial frames.
3. **ICMP Traffic:** Traced the standard Echo Request and Echo Reply sequence after the ARP cache is populated.

### 🛡️ SOC/Security Takeaway:
Understanding this normal baseline is essential for detecting **ARP Spoofing/Poisoning** (Man-in-the-Middle attacks) and **MAC Flooding**. In a SOC environment, recognizing abnormal broadcast spikes or unauthorized ARP replies is the first step in identifying internal reconnaissance or lateral movement.
