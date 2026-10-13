
### 1. What is an IPv4 Address?

- IPv4 stands for Internet Protocol version 4.
    
- It is a 32-bit address used to identify a device on a network.
    
- It is written as four numbers separated by dots.
    
- Example: `192.168.1.10`
    
- Each number ranges from 0 to 255.
    

### 2. Network Part and Host Part

- An IPv4 address has two main parts: the network part and the host part.
    
- **Network part:** Identifies the network to which a device belongs.
    
- **Host part:** Identifies a device within that network.
    
- The subnet mask or CIDR prefix tells us which bits belong to the network.
    

Example: `192.168.1.10/24`

- Network address: `192.168.1.0`
    
- Host address: `192.168.1.10`
    
- `/24` means the first 24 bits represent the network part.
    

### 3. Private IPv4 Address Ranges

Private IP addresses are used inside local networks, such as homes, colleges, and offices. They are not directly routable over the public internet.

The three private IPv4 ranges are:

- `10.0.0.0/8` — Used in large private networks.
    
- `172.16.0.0/12` — Covers addresses from `172.16.0.0` to `172.31.255.255`.
    
- `192.168.0.0/16` — Commonly used in home and small office networks.
    

Examples:

- `10.0.0.5`
    
- `172.16.1.10`
    
- `192.168.1.10`
    

### 4. Public vs Private IP Addresses

**Public IP Address**

- Used to identify a network or device on the public internet.
    
- Must be globally routable and assigned appropriately.
    
- Example: `8.8.8.8`
    

**Private IP Address**

- Used for communication within private networks.
    
- Can be reused in different homes or organizations.
    
- Usually accesses the internet through a router using NAT (Network Address Translation).
    

### 5. Loopback Address (127.0.0.1)

- `127.0.0.1` is the IPv4 loopback address, commonly called `localhost`.
    
- It refers to the same device on which it is used.
    
- It is used to test local networking and network software.
    
- Traffic sent to this address stays within the local device.
    

Example: Typing `127.0.0.1` into a browser may open a website running on your own computer, if one is configured.

### Summary

- IPv4 is a 32-bit addressing system.
    
- Network part identifies the network; host part identifies a device within it.
    
- Private IP ranges are `10.0.0.0/8`, `172.16.0.0/12`, and `192.168.0.0/16`.
    
- Public IP addresses are used for internet routing.
    
- `127.0.0.1` refers to your own device.