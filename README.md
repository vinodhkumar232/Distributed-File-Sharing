# Distributed-File-Sharing
A secure, decentralized, and scalable peer-to-peer file-sharing system. This project enables fast, encrypted data transfer across a network of distributed nodes without a central server.


# 📡 Distributed File Sharing

A **decentralized file-sharing system** that enables **secure, fast, and reliable data transfer** across distributed nodes. This project is designed to provide **peer-to-peer (P2P) file sharing** without the need for a centralized server, ensuring **fault tolerance, scalability, and redundancy**.

---

## ✨ Key Features

- **Peer-to-Peer File Transfer**: Direct client-to-client communication eliminates the need for a central server, improving efficiency and resilience.
- **End-to-End Encryption**: Files are secured with **AES encryption** to ensure confidentiality during transfer.
- **Fault Tolerance & Redundancy**: Data is replicated across multiple nodes, ensuring the system remains operational even if some nodes go offline.
- **Scalable Architecture**: The system is designed to seamlessly integrate new peers and nodes, allowing it to grow with demand.
- **Fast & Reliable**: Optimized socket-based communication ensures quick and dependable file transfers.
- **Modular Design**: The project structure is clear and easy to maintain, with separate modules for client, server, and utility functions.

---

## 📂 Project Structure

```bash
distributed-file-sharing/
│── client.py          # Client-side application for uploading & downloading files
│── server.py          # Server-side node handling file storage and requests
│── utils.py           # Utility functions (encryption, hashing, etc.)
│── requirements.txt   # Python dependencies
│── README.md          # Project documentation
│── LICENSE            # Open-source MIT License
