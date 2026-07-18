# TCP vs UDP

## What is TCP?

TCP (Transmission Control Protocol) is a connection-oriented transport layer protocol that provides reliable, ordered, and error-checked delivery of data between devices.

### Features
- Connection-oriented
- Reliable data delivery
- Uses a 3-way handshake
- Error checking and retransmission
- Guarantees packet order

### Common Uses
- HTTP/HTTPS
- SSH
- FTP
- Email (SMTP, IMAP, POP3)

---

## What is UDP?

UDP (User Datagram Protocol) is a connectionless transport layer protocol. It is faster than TCP because it does not establish a connection or guarantee delivery.

### Features
- Connectionless
- Faster than TCP
- No delivery guarantee
- No packet ordering
- Low overhead

### Common Uses
- DNS
- Online Gaming
- Video Streaming
- Voice over IP (VoIP)

---

# TCP vs UDP

| Feature | TCP | UDP |
|---------|-----|-----|
| Connection | Yes | No |
| Reliable | Yes | No |
| Speed | Slower | Faster |
| Packet Order | Guaranteed | Not Guaranteed |
| Error Recovery | Yes | No |
| Handshake | 3-Way Handshake | No Handshake |

---

# TCP 3-Way Handshake

1. Client → Server: SYN
2. Server → Client: SYN-ACK
3. Client → Server: ACK

Connection Established ✅

---

# Real-Life Example

TCP is like sending a registered courier.
- Delivery is confirmed.
- Lost packages are resent.
- Everything arrives in order.

UDP is like sending a postcard.
- It is faster.
- No confirmation.
- It may be lost or arrive out of order.

---

# Advantages of TCP

- Reliable
- Secure communication
- Error recovery
- Ordered delivery

# Advantages of UDP

- Very fast
- Low latency
- Efficient for real-time applications

---

# Interview Questions

### What does TCP stand for?
Transmission Control Protocol.

### What does UDP stand for?
User Datagram Protocol.

### Which protocol is faster?
UDP.

### Which protocol uses a 3-way handshake?
TCP.

### Which protocol is used by HTTPS?
TCP.

### Which protocol is commonly used by DNS?
UDP.

---

# Summary

TCP provides reliable communication and is used when data accuracy is important.

UDP provides fast communication and is used when speed is more important than guaranteed delivery.
