# Lab---Build-a-Simple-# Lab - Build a Simple Network

## Objective
Set up a basic Ethernet network using two PCs and a wireless router, configure static IP addresses, and verify connectivity using ping. In this lab, I set up a basic Ethernet network using two PCs and a wireless router. I connected each PC to the router with Ethernet cables, assigned them static IP addresses, and confirmed they could communicate by using the ping command. I also learned how to check network settings and troubleshoot issues like firewall blocking.

## Tools Used
- Wireless router with at least two switchports
- 2 PCs running Windows 10 with wired NICs
- 2 Ethernet patch cables

## Summary of Tasks
1. **Set Up the Network Topology**
   - Powered on all devices.
   - Connected:
     - `PC-A` NIC → Wireless Router switchport 1
     - `PC-B` NIC → Wireless Router switchport 2
   - Verified port link lights turned amber and then green to confirm physical connectivity.

2. **Configure Static IP Addresses**
   - **PC-A**
     - IP Address: `192.168.1.10`
     - Subnet Mask: `255.255.255.0`
   - **PC-B**
     - IP Address: `192.168.1.11`
     - Subnet Mask: `255.255.255.0`
   - Applied settings through **Control Panel → Network and Internet → Change adapter options → Ethernet Properties**.

3. **Verify PC Settings and Connectivity**
   - Ran `ipconfig /all` on each PC to confirm correct IP configuration.
   - Used `ping` to test connectivity:
     - From PC-A to PC-B: `ping 192.168.1.11`
     - From PC-B to PC-A: `ping 192.168.1.10`
   - Troubleshot potential issues such as Windows Firewall blocking ICMP.

## Outcome
- Successfully built a functional Ethernet network between two PCs.
- Configured static IP addresses for direct communication.
- Verified connectivity through ping tests in both directions.

## Skills Demonstrated
- Ethernet network topology setup
- Static IP address configuration on Windows 10
- Connectivity verification using `ping`
- Basic troubleshooting for ICMP/firewall issues
- Understanding link light indicators for network interfaces

## Notes
If pings are unsuccessful, check for:
- Incorrect cabling or port selection
- Incorrect IP configuration
- Firewall blocking ICMP requests
In this lab, I set up a basic Ethernet network using two PCs and a wireless router. I connected each PC to the router with Ethernet cables, assigned them static IP addresses, and confirmed they could communicate by using the ping command. I also learned how to check network settings and troubleshoot issues like firewall blocking.

