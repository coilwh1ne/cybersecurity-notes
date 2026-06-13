# Intro to Networking

### What is a Network?

- A network consists of two or more connected devices.

> For example: Two or more computers connected together create a network.

---

### Internet and Internet Protocol (IP)

- The Internet is a very big network, consisting of smaller networks (private and public).
- Internet Protocol (IP) represents the rules by which devices in a network communicate with each other. There are 2 versions of IP:
  
1. IPv4: consists of 4 octets, where every octet can be in the 0 - 255 range.
       
    > For example: 130.23.0.25
       
2. IPv6: consists of 8 hextets, where every hextet can be in the 0 - ffff range (in hex).

    > For example: 2001:0db8:85a3:0067:0003:8a2e:0370:733f

---

### Public and Private IP addresses

We can separate IP addresses into 2 categories:

1. Private IP address
2. Public IP address

A private IP address is used to identify a device among other devices within a local network, whereas a public IP address is used to identify a device on the Internet.

| IP address | IP address type |
| :--- | :---: |
| 192.168.0.23 | Private |
| 10.130.20.2 | Private |
| 129.30.0.3 | Public |
| 49.100.0.5 | Public |

---

### MAC address

A MAC (Media Access Control) address is a device's physical network interface address. A network interface card (a microchip on the motherboard) gets this address at the factory.

It consists of 12 hex numbers separated by colons (`:`). The first 3 pairs represent the vendor's code who built this microchip.

> For example: `a4:c3:f0:85:ac:2d` (for this interface, the vendor is Intel).

A MAC address can be faked; this process is called ```spoofing```. For example, it can be used to bypass a firewall.

---

### Ping (ICMP)

Ping is a popular tool for checking the connection to a server on the Internet. Ping can also check the connection to another device in a local network.

It uses ICMP (Internet Control Message Protocol) packets to determine connection performance to a website, server, or another device.

To ping anything, we should write:

```bash
ping -c 4 target
```

where `target` is an IP address or a URL.
