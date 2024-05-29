# Secure Communication in Ethical IoT: A Demonstration with RISC-V

# Introduction
In the ever-expanding world of the Internet of Things (IoT), ensuring the security of communication between devices is paramount. This project showcases a fundamental concept in secure communication: **end-to-end encryption**. We utilize the power of the RISC-V architecture on the VSDSquadron microcontroller to demonstrate how data can be scrambled during transmission and only be unraveled by the intended recipient.

This project aligns perfectly with the hackathon's themes of **ethical IoT** and **security with RISC-V**. By focusing on secure communication, we address ethical concerns surrounding data privacy and unauthorized access within IoT systems. 

### Why is this relevant?
End-to-end encryption fosters trust in IoT systems. It guarantees that the data exchanged between devices remains confidential, even if intercepted by a malicious third party. This is crucial for scenarios where sensitive information, like sensor data from a smart home or medical device readings, is being transmitted.

### Advantages of RISC-V?
The RISC-V architecture provides an open-source and flexible platform for implementing cryptographic algorithms like RSA encryption. This allows developers to tailor security measures to specific needs while ensuring transparency and community-driven development.

# Overview
This project demonstrates secure communication using the VSDSquadron microcontroller. Here's a basic overview:

<div align="center">
  
| Step Number | Step | Step Description |
|---|---|---|
| 1 | **User A enters message** | User A types a message on the shared keypad. |
| 2 |**RISC-V encrypts message** | The microcontroller encrypts the message using RSA. |
| 3 | **Display encrypted message** | User A's OLED screen shows the encrypted message. |
| 4 | **Simulated transmission** | The encrypted message is fed for decryption. |
| 5 | **RISC-V decrypts message** | The microcontroller decrypts the message using a different key. |
| 6 | **Display decrypted message** | User B's OLED screen displays the decrypted message. |

</div>

**User Switch:** Users take turns sending and receiving encrypted messages using the same process.



# Components

# Circuit Connection Diagram

# Table for Pin Connections
