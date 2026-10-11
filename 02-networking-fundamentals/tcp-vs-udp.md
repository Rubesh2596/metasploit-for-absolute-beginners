# TCP vs. UDP

## What is TCP?

TCP stands for Transmission Control Protocol.

### Why do we need it?

TCP is reliable and ensures data arrives correctly.

### Simple explanation

TCP is like sending a package with tracking information. The system checks whether it arrived as expected.

### Common uses

- Web traffic (`HTTP`, `HTTPS`)
- SSH
- Email

### Key traits

- Reliable
- Connection-oriented
- Ordered delivery

---

## What is UDP?

UDP stands for User Datagram Protocol.

### Why do we need it?

UDP is lighter and faster, but less reliable.

### Simple explanation

UDP is like sending a message without waiting for confirmation.

### Common uses

- DNS
- Streaming media
- VoIP
- DHCP

### Key traits

- Fast
- Lightweight
- Connectionless

---

## TCP vs. UDP table

| Feature | TCP | UDP |
|--------|-----|-----|
| Connection required | Yes | No |
| Reliable delivery | Yes | No |
| Ordered delivery | Yes | No |
| Typical use | Web, SSH, email | DNS, media |
| Speed | Slower | Faster |

### Practice exercise

Explain which protocol would be better for a website and which would be better for streaming audio.

### Common mistakes

- Thinking UDP is always better.
- Ignoring the difference between reliability and speed.

### Recap

TCP is reliable and ordered; UDP is faster and simpler.

### Review questions

1. What does TCP do better than UDP?
2. Which protocol is commonly used for DNS?
3. Why might UDP be used for streaming?

## Next steps

Continue to [Module 03: Kali Linux Basics](../03-kali-linux-basics/terminal-commands.md).
