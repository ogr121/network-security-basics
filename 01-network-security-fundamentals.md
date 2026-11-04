# 01 – Network Security Fundamentals

## What is network security?

Network security means protecting the devices, data and connections in a network from attacks, misuse and accidents. Its aim is to keep the network working and the data safe.

## The CIA triad

| Goal | Meaning | Example |
|------|---------|---------|
| Confidentiality | Only the right people can see data | Encrypting Wi-Fi traffic |
| Integrity | Data is not changed without permission | Checking file hashes |
| Availability | Systems work when people need them | Backups and spare internet links |

## Defence in depth

No single control can stop every attack. Defence in depth means using many layers, so if one layer fails, another one still protects the network.

1. **Perimeter:** firewall, intrusion prevention system (IPS)
2. **Network:** segmentation, VLANs, secure Wi-Fi
3. **Host:** antivirus, patching, device hardening
4. **Application:** secure settings, input checks
5. **Data:** encryption, backups, access control
6. **People:** training and clear security rules

## Principle of least privilege

Users and devices should only get the access they need for their work. For example, a receptionist does not need access to the server room network.

## Common ports and services

| Port | Protocol | Use | Security note |
|------|----------|-----|---------------|
| 22 | SSH | Secure remote login | Use keys and strong passwords |
| 23 | Telnet | Old remote login | Insecure. Disable it. |
| 25 | SMTP | Sending email | Restrict to the mail server |
| 53 | DNS | Domain names | Watch for DNS tunnelling |
| 80 | HTTP | Web (not encrypted) | Redirect to HTTPS |
| 443 | HTTPS | Secure web | Keep certificates up to date |
| 3389 | RDP | Remote desktop | Do not expose to the internet |

Only open the ports that the business really needs.
