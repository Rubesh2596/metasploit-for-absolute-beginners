# Ports and Protocols

## 1. What are ports?

A port is a number used to distinguish one service from another on the same device.

### Why do we need it?

A computer can run multiple services at once, and ports help direct traffic to the correct one.

### Simple explanation

Think of a computer like a building with many doors. Each door leads to a different service.

### Important terminology

- Port: a numbered endpoint.
- Service: a program waiting for network access.
- Listener: a service waiting for incoming connections.

### Common ports

| Port | Common use | Protocol |
|------|------------|----------|
| 22 | SSH | TCP |
| 53 | DNS | UDP/TCP |
| 80 | HTTP | TCP |
| 443 | HTTPS | TCP |
| 445 | SMB | TCP |

### Example

A web server usually listens on port 80 for HTTP or 443 for HTTPS.

### Practice exercise

Write down which port is commonly used for HTTPS.

### Common mistakes

- Thinking a port is the same as an IP address.
- Forgetting that one machine can run many services.

### Recap

Ports allow a host to route traffic to the correct service.

### Review questions

1. What is a port?
2. Why are ports useful?
3. Which port is commonly used for HTTPS?

---

## 2. What is a protocol?

A protocol is a set of rules for how devices communicate.

### Why do we need it?

Without protocols, devices would not know how to format or read data.

### Simple explanation

Protocols are like traffic rules for the internet.

### Example protocols

- HTTP: used for websites.
- HTTPS: secure websites.
- DNS: resolves names to IPs.
- TCP and UDP: transport protocols.

### Practice exercise

List two protocols and explain what each is used for.

### Recap

Protocols define how communication works between devices.

### Review questions

1. What is a protocol?
2. Why are protocols important?
3. Name one protocol used for web traffic.

---

## 3. Client and server

### Client
A client requests a service.

### Server
A server provides a service.

### Simple explanation

A browser is a client. A website is served by a server.

### Example

When you visit a page, your browser sends a request and the server responds.

### Practice exercise

Name one client and one server in a home network.

### Recap

Clients request services, and servers provide them.

### Review questions

1. What is a client?
2. What is a server?
3. Give one example of both.

---

## 4. Listening services

A listening service waits for incoming connections or requests.

### Why do we need it?

Web servers and SSH services must listen before traffic can reach them.

### Simple explanation

A listening service is like a shopkeeper waiting at the front door.

### Example

An HTTP service may listen on port 80 or 443.

### Practice exercise

Explain what it means when a service is in a listening state.

### Recap

Listening services wait on specific ports for requests.

### Review questions

1. What does a listening service do?
2. Why are ports important?
3. Which service might listen on port 80?

---

## 5. Basic routing

Routing is the process of choosing a path for network traffic.

### Why do we need it?

Devices often do not talk directly to each other across all networks.

### Command example

```bash
ip route
```

This shows the route table and default route.

### Practice exercise

Run `ip route` and look for the `default via` line.

### Recap

Routing moves data across networks.

### Review questions

1. What is routing?
2. Why is it important?
3. What command helps inspect routes?

## Next steps

Continue to [TCP vs. UDP](./tcp-vs-udp.md).
