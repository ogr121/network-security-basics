# 03 – Firewalls and Network Segmentation

## Firewalls

A firewall checks network traffic and allows or blocks it using rules.

| Type | How it works |
|------|--------------|
| Packet filtering | Checks IP address, port and protocol |
| Stateful | Also remembers active connections |
| Next-generation (NGFW) | Adds application control and intrusion prevention |

### Good firewall rule practice

- Use **default deny**: block everything, then allow only what is needed.
- Give each rule a clear purpose and an owner.
- Review rules at least every six months and delete old rules.
- Keep firewall software updated.
- Save logs and check them regularly.

### Example rule set

| No. | Source | Destination | Port | Action | Reason |
|-----|--------|-------------|------|--------|--------|
| 1 | Staff LAN | Internet | 80, 443 | Allow | Web browsing |
| 2 | Internet | Web server (DMZ) | 443 | Allow | Public website |
| 3 | Guest Wi-Fi | Staff LAN | Any | Deny | Keep guests separate |
| 4 | Any | Any | Any | Deny | Default deny |

## Network segmentation

Segmentation splits one big network into smaller parts. If an attacker enters one part, they cannot easily move to the others.

- **VLANs:** separate groups such as Staff, Servers, Guests and CCTV.
- **DMZ:** a separate zone for public servers, such as a website, so the internal network stays hidden.
- **Guest Wi-Fi:** only gives internet access.

```
Internet
   |
[Firewall]
   |-- DMZ (web server)
   |-- Staff VLAN
   |-- Server VLAN
   |-- Guest VLAN
```

## Other useful controls

- **VPN** for safe remote access
- **Wi-Fi security:** use WPA3 (or WPA2 at minimum) and a strong passphrase
- **Monitoring:** collect logs and set alerts for unusual activity
