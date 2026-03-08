# Home-Network-Design-Wireless-Security-Implementation
## Project: Home Network Design & Wireless Security Implementation
Platform: Cisco Packet Tracer

Status: Completed & Verified

### 📝 Project Objective
The goal of this project was to design and deploy a functional home network for a residential client. The project involved establishing a physical connection to a Cable Provider network, configuring a wireless router (SOHO) via a GUI, and ensuring seamless connectivity for both wired and wireless clients.

### 🛠️ Technical Implementation
1. Physical Layer & Media Connectivity
Signal Splitting: Implemented a Cable Splitter to separate Video (Television) and Data (Cable Modem) services via Coaxial cabling.

Internet Gateway: Connected the Cable Modem to the Wireless Router's Internet (WAN) Port using Copper Straight-Through cabling.

Wired LAN: Established Ethernet connections for stationary PCs (Office and Bedroom) to the router’s GigabitEthernet switch ports.

2. Router Configuration (GUI-based)
DHCP Management: Configured the internal DHCP server to limit the address pool to 10 maximum users to reduce the network's attack surface in a high-density area.

Administrative Security: Hardened the router by changing default manufacturer credentials (admin/admin) to a complex, secure password (MyPassword1!).

Wireless LAN (WLAN) Setup: * SSID: MyHome (2.4 GHz band).

Security Protocol: Implemented WPA2-Personal (AES)—the strongest encryption available on the hardware.

Authentication: Set a Pre-Shared Key (PSK) to prevent unauthorized access.

3. Testing & Connectivity Verification
Dynamic Addressing: Verified that all clients (Laptop and PCs) successfully pulled IPv4 addresses in the 192.168.x.x range via DHCP.

End-to-End Connectivity: Confirmed successful HTTP requests from all internal hosts to the external web server (skillsforall.srv).

Wireless Association: Successfully associated the Living Room Laptop with the Access Point using the configured WPA2 credentials.
