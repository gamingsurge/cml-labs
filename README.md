# CML Labs

A collection of network simulation labs I created during my CCNP journey using [Cisco Modeling Labs (CML)](https://www.cisco.com/go/cml).

This repo is designed to:
- Serve as a reference for CCNP-level technologies
- Demonstrate real-world and exam-aligned topologies
- Allow direct integration with CML 2.9+ via external repository support

---

## 🧰 Lab Categories

The labs are organized into directories by topic:

| Category   | Description                                |
|------------|--------------------------------------------|
| `routing/` | OSPF, EIGRP, BGP, redistribution, VRF      |
| `switching/` | VLANs, STP, EtherChannel, port security  |
| `security/` | ACLs, zone-based firewall, SSH hardening |
| `overlays/` | CML overlays used in specific labs        |
| `templates/` | Starting point topologies or node configs|

Each lab file is in `.virl2` format and can be opened directly in Cisco Modeling Labs.

---

## 🛠️ How to Use with CML

To use this repo in CML 2.9+:

1. Go to **Tools → Lab Management → Lab Repositories**
2. Click **Add Repository**
   - **Name**: `sergiolabs`
   - **URL**: `https://github.com/gamingsurge/cml-labs.git`
   - Leave Folder blank (or specify if using a subdirectory)
3. Click **Refresh All**
4. Labs will appear under **File → Open Lab → External Labs**

---

## 🧪 Example Labs

- `routing/ospf-basic.virl2`: 3-router topology demonstrating OSPFv2 areas and DR/BDR election
- `switching/stp-priority.virl2`: Root bridge election and port role demo
- `security/zbf.virl2`: Zone-based firewall with inspection and logging

---

## 💡 Contributing

These labs are based on real studies and troubleshooting scenarios. You're welcome to fork or clone and expand upon them.

---

## 🔐 Requirements

- Cisco Modeling Labs 2.9 or later
- Appropriate images (IOSv, IOSvL2, etc.) licensed and uploaded in your CML instance

---

## 📜 License

MIT License — see [LICENSE](LICENSE) for details.

