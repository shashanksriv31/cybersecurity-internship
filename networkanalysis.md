# cybersecurity-internship  
Task 5 of the Cybersecurity Internship

# Wireshark Network Traffic Analysis

## What's this project about?

This project focuses on learning how to capture and analyze network traffic using **Wireshark**. It involves identifying and interpreting different protocols such as **DNS**, **HTTP**, and **OCSP**, and observing how data is transmitted over a network.

---

## Tools I used

- **Wireshark**: A GUI-based packet sniffer and protocol analyzer used for real-time traffic inspection.
- **Browser & ping tools**: To generate DNS, HTTP, and ICMP traffic.

---

## How I did it 📝

1. I installed Wireshark on Kali Linux using the terminal.
2. Launched Wireshark and selected the active network interface (`eth0`).
3. Started packet capture while browsing websites and using the ping command.
4. Applied filters like `http`, `dns`, and `ocsp` in Wireshark to focus on specific protocol traffic.
5. Analyzed each packet’s source/destination, port numbers, and message type.
6. Took screenshots of the filtered traffic and saved them for documentation.

---

## Code snippets

To install Wireshark in Kali Linux:

bash
sudo apt update
sudo apt install wireshark -y

Filters used in Wireshark:

http – for web requests

![Screenshot 2025-06-30 115016](https://github.com/user-attachments/assets/f08ec6ca-7fe0-4151-bd68-632eb4711e38)
![Screenshot 2025-06-30 115038](https://github.com/user-attachments/assets/de0a7d59-2e77-4894-ae74-6c88bc54b426)
![Screenshot 2025-06-30 120328](https://github.com/user-attachments/assets/2d3fe51e-b571-4a1a-a896-7684304f7029)

dns – for domain name queries

![Screenshot 2025-06-30 115118](https://github.com/user-attachments/assets/f7e421ed-f49b-40eb-a295-c7d7cd771e13)
![Screenshot 2025-06-30 115232](https://github.com/user-attachments/assets/3625ca1f-aa18-4d13-9e0e-60934087764d)

ocsp – for certificate status checks

![Screenshot 2025-06-30 120311](https://github.com/user-attachments/assets/30ea6c92-18a3-4740-8447-19c7c546f731)
![Screenshot 2025-06-30 120328](https://github.com/user-attachments/assets/2020d458-d587-4ab1-a648-fcda718dd8a0)

What I learned

How to use Wireshark to capture live traffic.

How to analyze DNS, HTTP, and OCSP protocols.

How certificate validation works using OCSP.

How to apply and use filters in Wireshark for effective inspection.

How internal (e.g., 10.0.2.x) and public IPs (e.g., 142.251.221.163) are used in network communication.

