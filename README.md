# ANOM 2.0
**Decentralized. Unstoppable. Anonymous Chat Network.**

## What is ANOM 2.0?
ANOM 2.0 is a fully decentralized, peer-to-peer chat system with onion-style encryption.
- No servers
- No registration
- No tracking
- Impossible to shut down

Every user is a node. Every message hops through multiple nodes anonymously.
Built for privacy lovers, freedom fighters, and those who believe in unstoppable communication.

---

## Key Features
- **Completely decentralized** — no central authority, no single point of failure.
- **Onion routing** — messages are layered with encryption and pass through multiple nodes.
- **Usernames** — simple username system for a friendlier chatting experience.
- **Anonymous identity** — only public keys and usernames, no IP tracking.
- **Fully Python-based** for now, with mobile and desktop apps coming soon.

---

## How Does It Work? (In simple words)
1. Each device running ANOM 2.0 becomes a node in the network.
2. Messages are encrypted and sent through random nodes, making it impossible to trace.
3. Nodes relay messages without knowing their content.
4. The receiver decrypts the final layer and reads the message.

---

## Text Diagram of the Network  
```
[User A]
   |
   |  (Encrypt message with multiple layers)
   |
  [Node 1] ----> [Node 2] ----> [Node 3] ----> [User B]
  (Peels 1 layer)   (Peels 2nd layer)   (Peels last layer)
```

Each node only knows where to send the message next, not who sent it or what it contains.

---

## Roadmap
- ✅ CLI prototype (Current version)
- ✅ Username support
- ✅ Relay and retry logic
- ⏳ Android app (coming soon)
- ⏳ Windows desktop app interface (coming soon)
- ⏳ Automatic peer discovery

---

## How to Use (For the upcoming release)
- Install Python 3.9+
- Clone this repo
- Run `python anom.py`
- Set username and start chatting by connecting to peers

---

## Legal Notice
ANOM 2.0 is provided as-is for educational and privacy research purposes.  
Users are responsible for following their local laws.

---

## Join the movement.  
**ANOM 2.0 — Unstoppable communication for a free world.**

