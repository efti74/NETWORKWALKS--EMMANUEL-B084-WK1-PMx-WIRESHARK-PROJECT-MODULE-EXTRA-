# 🔎 Wireshark SOC Lab — Week 01 Extra Project

Hands-on Wireshark practice completed as an **extra project related to Week 01** of the NetworkWalks cybersecurity program. This repository records lab results and the skills practised through network traffic analysis.

<p align="center">
  <strong>Wireshark SOC Lab Practice</strong><br>
  <a href="https://networkwalks.com/wireshark/">Practice labs at NetworkWalks</a>
</p>

---

## 📌 Project Overview

I completed NetworkWalks Wireshark SOC Labs 3–8 and two Wireshark quizzes. The supplied completion screenshots show **100% scores** for each of these results.

The exercises focus on packet capture, TCP stream inspection, suspicious traffic identification, plaintext credential exposure, brute-force indicators, and VoIP traffic analysis.

> The screenshots document the displayed completion results. They are not a substitute for detailed packet captures or investigation reports.

## 🎯 Objectives

- Practise inspecting network traffic with Wireshark.
- Follow TCP streams to understand client-server communication.
- Recognize traffic patterns related to scanning and brute-force attempts.
- Understand the risks of credentials transmitted over plaintext HTTP.
- Explore VoIP call signalling and related protocol fields.
- Document hands-on SOC learning in a GitHub portfolio.

## 🧪 Lab Environment

| Item | Details |
|---|---|
| Program context | NetworkWalks — Week 01 extra project |
| Main tool | Wireshark |
| Focus | SOC and network traffic analysis |
| Practice platform | [NetworkWalks Wireshark Labs](https://networkwalks.com/wireshark/) |
| Labs documented | Labs 3–8 |
| Quizzes documented | Wireshark Quiz and Advanced-Level Wireshark Quiz |
| Scores shown | 100% on all eight supplied result screenshots |

## 🧠 Labs Completed

| Lab | Topic | Skills practised |
|---|---|---|
| Lab 3 | Identify the Attacker’s IP | Filter SYN packets, identify source and target IPs, review ports, and investigate possible scanning |
| Lab 4 | Follow TCP Stream | Find a chat port, follow a TCP stream, and inspect application data |
| Lab 5 | Follow TCP Stream, Part 2 | Locate streams and pages, inspect transferred content, and review related details |
| Lab 6 | HTTP Plain Text Credentials | Examine HTTP traffic and understand the risks of credentials sent without encryption |
| Lab 7 | Brute Force Catch | Review repeated login attempts, failure and success codes, and attack indicators |
| Lab 8 | VoIP Call Replay | Examine call setup, voice protocols, caller details, and related signalling information |

## 📸 Lab Result Screenshots

Screenshots are arranged in order from Lab 3 through Lab 8.

### Lab 3 — Identify the Attacker’s IP

![Lab 3 result showing 100/100](assets/lab-03-identify-attackers-ip.png)

### Lab 4 — Follow TCP Stream

![Lab 4 result showing 100/100](assets/lab-04-follow-tcp-stream.png)

### Lab 5 — Follow TCP Stream, Part 2

![Lab 5 result showing 100/100](assets/lab-05-follow-tcp-stream-part-2.png)

### Lab 6 — HTTP Plain Text Credentials

![Lab 6 result showing 100/100](assets/lab-06-http-plaintext-credentials.png)

### Lab 7 — Brute Force Catch

![Lab 7 result showing 100/100](assets/lab-07-brute-force-catch.png)

### Lab 8 — VoIP Call Replay

![Lab 8 result showing 100/100](assets/lab-08-voip-call-replay.png)

## 📝 Wireshark Quiz Results

### Wireshark Quiz

![Wireshark quiz result showing 100 percent](assets/wireshark-quiz-100-percent.png)

### Wireshark Quiz — Advanced Level

![Advanced-level Wireshark quiz result showing 100 percent](assets/wireshark-advanced-quiz-100-percent.png)

## 🔐 SOC Analyst Takeaways

- **Packet analysis:** Protocol fields and packet details help explain how systems communicate.
- **TCP stream inspection:** Following a stream can make application-level conversations easier to understand.
- **Reconnaissance detection:** SYN traffic and connection patterns may indicate port scanning.
- **Credential exposure:** Plaintext protocols can expose sensitive information when traffic is not encrypted.
- **Brute-force investigation:** Repeated authentication failures followed by a success can be useful indicators to correlate.
- **VoIP analysis:** Signalling and call-related fields can help reconstruct parts of a voice session.
- **Evidence-based investigation:** Validate conclusions against packet data, timestamps, endpoints, and surrounding traffic rather than relying on a single indicator.

These are general lessons from the lab topics. Actual findings should be verified against the relevant packet capture and environment.

## 🔗 Practice Link

**[NetworkWalks Wireshark Labs — https://networkwalks.com/wireshark/](https://networkwalks.com/wireshark/)**

## 👤 Author

**Md. Sibgatur Rahman Efti**

- GitHub: [@efti74](https://github.com/efti74)
- LinkedIn: [Md. Sibgatur Rahman Efti](https://www.linkedin.com/in/md-sibgatur-rahman-efti-861b67207/)

## ⚠️ Disclaimer

This repository documents educational lab practice. Capture or investigate traffic only on networks and systems you own or are authorized to assess. Do not intercept other people's communications without permission.

---

*Week 01 — Extra Project | Wireshark and SOC Practice*
