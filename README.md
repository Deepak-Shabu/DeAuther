README.md
# 🚨 Wi-Fi DoS (Deauthentication) Attack Detection System

## Overview
This project implements a real-time detection and monitoring system for Wi-Fi Denial-of-Service (Deauthentication) attacks by analysing IEEE 802.11 management frames. The system demonstrates SOC-style detection, investigation, and forensic analysis of wireless attacks using Python-based tooling.

## Key Features
- Real-time detection of Wi-Fi deauthentication (DoS) attacks
- Packet-level inspection of IEEE 802.11 management frames
- False-positive awareness by distinguishing legitimate vs malicious behaviour
- Forensic artefact storage using MongoDB
- Web-based dashboard for investigation and reporting

## Architecture & Workflow
1. Wireless adapter operates in monitor mode  
2. Scapy captures and inspects 802.11 frames  
3. Deauthentication patterns are detected  
4. Attack artefacts are stored in MongoDB  
5. Flask dashboard visualises incidents  

## Technologies Used
- Python 3
- Scapy
- Flask
- MongoDB
- Aircrack-ng
- Linux

## Security Use Case
Wi-Fi deauthentication attacks are commonly used to disrupt availability and enable follow-on attacks. This project demonstrates detection and investigation techniques relevant to SOC and Incident Response roles.

## Disclaimer
This project was developed strictly for educational and defensive security purposes. All testing was conducted in a controlled environment on authorised devices only.

## Author
Deepak Shabu  
MSc Cyber Security | Aspiring Security Analyst
