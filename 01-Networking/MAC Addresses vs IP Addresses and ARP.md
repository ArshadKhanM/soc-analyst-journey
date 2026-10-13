
### 1. MAC Address

- MAC stands for Media Access Control.
- It is a hardware address used to identify a network interface on a local network.
- A MAC address is usually 48 bits (6 bytes) long.
- It is written in hexadecimal format.
- Example: `00:1A:2B:3C:4D:5E`

### 2. IP Address

- IP stands for Internet Protocol.
- It is a logical address used to identify a device on an IP network.
- An IPv4 address is 32 bits long.
- It helps route data between different networks.  
- Example: `192.168.1.10`


### 3. Difference Between MAC and IP Addresses

- MAC address identifies a network interface on the local network.
    
- IP address identifies a device's network-layer address.
    
- MAC addresses operate at the Data Link layer (Layer 2).
    
- IP addresses operate at the Network layer (Layer 3).
    
- MAC addresses are generally assigned to network interfaces, while IP addresses can change depending on the network.
    

### 4. What is ARP?

- ARP stands for Address Resolution Protocol.
    
- It is used in IPv4 networks to find the MAC address associated with a local IPv4 address.
    
- It helps devices send Ethernet frames to the correct device on the local network.
    
- ARP requests are sent as broadcasts on the local network.
    
- The device with the matching IP address usually replies with its MAC address.
    

### 5. How ARP Works

- A computer wants to send data to another device on the local network.
    
- It checks its ARP cache for the destination IP address.
    
- If the MAC address is not found, it broadcasts an ARP request.
    
- The device with the matching IP address sends an ARP reply containing its MAC address.
    
- The sender stores the mapping in its ARP cache.
    
- The sender uses the destination MAC address to deliver the Ethernet frame.
    

### 6. Example of ARP

- Computer A IP: `192.168.1.10`
    
- Computer B IP: `192.168.1.20`
    
- Computer B MAC: `00:1A:2B:3C:4D:5E`
    
- Computer A broadcasts an ARP request asking who has `192.168.1.20`.
    
- Computer B replies with its MAC address.
    
- Computer A sends the Ethernet frame to Computer B using that MAC address.
    

### Summary

- MAC addresses are used for local network frame delivery.
    
- IP addresses are used for communication across IP networks.
    
- ARP maps a local IPv4 address to a MAC address.
    
- ARP helps devices communicate on an IPv4 Ethernet network.