# IP Addresses

## 1. What is an IP address?

An IP address is a number used to identify a device on a network.

### Why do we need it?

Without IP addresses, devices would not know where to send data.

### Simple explanation

Think of it like a home address for a computer.

### Important terminology

- IPv4: a common address format such as `192.168.1.12`.
- IPv6: a newer format with more possible addresses.
- Host: a device on a network.

### Example

A laptop may have an address like `192.168.1.20`.

### Command example

```bash
ip addr
```

This command shows the machine’s network interfaces and their addresses.

### What the output means

You may see `lo` and `eth0` or `wlan0`. `lo` is the loopback interface, which refers to the local machine.

### Practice exercise

Run:

```bash
ip addr
```

Look for the `inet` line and write down what you see.

### Common mistakes

- Confusing a hostname with an IP address.
- Thinking every device has the same network address.

### Recap

An IP address helps identify a device on a network.

### Review questions

1. What is an IP address?
2. Why is it useful?
3. What does `ip addr` show?

---

## 2. Private vs. public IP addresses

### Private IP addresses
Private addresses are used inside a local network such as a home or lab.

Examples include:

- `192.168.0.0/16`
- `10.0.0.0/8`
- `172.16.0.0/12`

### Public IP addresses
Public addresses are used on the internet and are visible beyond a private network.

### Why this matters

A router often uses a private IP range on the inside and a public IP on the internet side.

### Practice exercise

Use:

```bash
ip addr
```

Identify whether your network interface is using a private address range.

### Recap

Private addresses are used locally; public addresses are used on the wider internet.

### Review questions

1. What is a private IP?
2. What is a public IP?
3. Why do home networks commonly use private IPs?

---

## 3. IPv4 basics

IPv4 addresses are written in dotted decimal form, like `192.168.1.10`.

### Why do we need it?

IPv4 is still used in many networks.

### Example

```text
192.168.1.10
```

### Practice exercise

Write three IPv4 addresses you might see on a lab network.

### Common mistakes

- Writing numbers above 255.
- Confusing IPv4 with a MAC address.

### Recap

IPv4 is a common method for identifying devices on a network.

### Review questions

1. What does an IPv4 address look like?
2. Why is IPv4 still common?
3. What is one common beginner mistake?

---

## 4. What is a subnet mask?

A subnet mask separates the network part of an address from the host part.

### Why do we need it?

It helps determine whether traffic stays local or goes to another network.

### Simple explanation

It is like a label telling a device which part of the address is the network and which part belongs to the device.

### Example

```text
192.168.1.25/24
```

The `/24` indicates the first 24 bits belong to the network.

### Practice exercise

Use `ip addr` and look for the subnet mask on your machine.

### Recap

The subnet mask helps decide what is local and what is remote.

### Review questions

1. What is a subnet mask?
2. Why is it useful?
3. What does `/24` mean?

---

## 5. What is a default gateway?

A default gateway is the device that sends traffic outside the local network.

### Why do we need it?

If a computer wants to reach another network, it sends traffic to the gateway.

### Command example

```bash
ip route
```

This shows the default route and gateway information.

### Practice exercise

Run the command and look for a line beginning with `default via`.

### Recap

The gateway helps route traffic to destinations outside the local subnet.

### Review questions

1. What is a gateway?
2. Why do we need one?
3. What command shows the route?

---

## 6. What is DNS?

DNS stands for Domain Name System. It turns names such as `example.com` into IP addresses.

### Why do we need it?

Humans are better at names than numbers.

### Simple explanation

DNS is like a phone book for the internet.

### Example

A browser asks DNS for the IP of a website before the request is sent.

### Practice exercise

Run:

```bash
ping -c 4 127.0.0.1
```

Then think about how a computer resolves a hostname such as `example.com`.

### Common mistakes

- Thinking DNS is the website itself.
- Forgetting that DNS is only a name-to-address lookup service.

### Recap

DNS translates names into numbers so people can use web addresses more easily.

### Review questions

1. What does DNS do?
2. Why is it useful?
3. What is a simple analogy for DNS?

---

## 7. What is DHCP?

DHCP stands for Dynamic Host Configuration Protocol. It automatically assigns IP addresses and basic network settings to devices.

### Why do we need it?

It helps devices join networks without manual configuration.

### Simple explanation

DHCP is like a network helper that gives out addresses when devices connect.

### Example

When you connect to Wi-Fi, your laptop may receive an IP address automatically via DHCP.

### Practice exercise

Explain in your own words what DHCP does.

### Recap

DHCP automatically assigns basic network settings.

### Review questions

1. What does DHCP do?
2. Why is it helpful?
3. What else might DHCP provide besides an IP address?

---

## 8. What is ARP?

ARP stands for Address Resolution Protocol. It maps an IP address to a MAC address on the local network.

### Why do we need it?

Hosts need to know the hardware address of devices nearby on the same network.

### Simple explanation

ARP is like asking: “Who owns this IP address on my local network?”

### Example

When a device wants to reach another computer on the same subnet, it may send an ARP request.

### Practice exercise

Explain the difference between an IP address and a MAC address in one sentence.

### Recap

ARP helps devices match IP addresses to hardware addresses on the same local network.

### Review questions

1. What is ARP?
2. Why is it useful?
3. What does it map?

---

## 9. How a computer connects to a website

A typical connection flow is:

1. You type a website name in the browser.
2. DNS resolves the name to an IP address.
3. Your device sends traffic to the destination.
4. A router or gateway decides the path.
5. The server responds with the data.

### Why do we need it?

This helps beginners understand what happens behind a simple web request.

### Simple explanation

The name becomes an address, and the data moves across a network until the website responds.

### Practice exercise

Write the steps in order for a browser requesting a webpage.

### Recap

Website access depends on naming, routing, and networking.

### Review questions

1. What role does DNS play?
2. Why is routing important?
3. Why do networking basics matter before Metasploit?

## Next steps

Continue to [Ports and Protocols](./ports-and-protocols.md).
