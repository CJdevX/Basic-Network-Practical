# Simple LAN Network

## 🎯 Objective
Set up a very basic Local Area Network(LAN) with:
- 1 Switch
- 5 PCs
- Static IP Configuration
- Verify Connectivity with ping

## 🛠️ Build Guide
1. Connect PCs to the switch using Straight Through Cable.
2. Assign static IPs on each PC.
3. Verify they are in the same subnet.
4. Test with `ping`.

### Step 1 – Setup Topology
- Connect PC0 → Switch Port 1
- Connect PC1 → Switch Port 2
- Connect PC2 → Switch Port 3
- Connect PC3 → Switch Port 4
- Connect PC4 → Switch Port 5

### Step 2 – Configure Static IPs
PC0:
- IP: 192.168.1.1
- Mask: 255.255.255.0

PC1:
- IP: 192.168.1.2
- Mask: 255.255.255.0

PC2:
- IP: 192.168.1.3
- Mask: 255.255.255.0

PC3:
- IP: 192.168.1.4
- Mask: 255.255.255.0

PC4:
- IP: 192.168.1.5
- Mask: 255.255.255.0
  
### Step 3 – Save Configurations
- Packet Tracer: Click on the PC → Desktop → IP Configuration

## ✅ Expected Result
  Every PC Connectivity must be Successful.
    Ex :- PC1 → PC2
