# 02 – Common Network Threats

| Threat | What it is | How to reduce the risk |
|--------|-----------|------------------------|
| Phishing | Fake emails or messages that trick users into giving passwords or opening malware | Staff training, email filtering, multi-factor authentication (MFA) |
| Malware and ransomware | Harmful software that steals, damages or locks data | Patching, antivirus, offline backups, limited user rights |
| Denial of Service (DoS/DDoS) | Too much traffic is sent to make a service stop working | Rate limiting, DDoS protection from the provider, spare capacity |
| Man-in-the-Middle (MitM) | An attacker secretly reads or changes traffic between two parties | Use HTTPS/TLS, VPN, avoid public Wi-Fi for work |
| Port scanning | An attacker checks which ports are open to find weak services | Close unused ports, firewall rules, monitor logs |
| Weak or default passwords | Easy-to-guess passwords on routers and devices | Change defaults, use long passwords, enable MFA |
| Rogue access points | An unauthorised Wi-Fi device connected to the network | Wireless scans, port security, regular network checks |
| Insider threat | An employee misuses access on purpose or by mistake | Least privilege, logging, user awareness |

## Example attack flow (ransomware)

1. A user clicks a link in a phishing email.
2. Malware is installed on the computer.
3. The malware spreads to other devices on a flat network.
4. Files are encrypted and a ransom is demanded.

**Where the attack could have been stopped:** email filtering (step 1), patching and antivirus (step 2), network segmentation (step 3), and offline backups (step 4).

## Warning signs

- Very slow network without a clear reason
- Unknown devices on the network
- Many failed login attempts in the logs
- Unusual traffic at night or to strange countries
