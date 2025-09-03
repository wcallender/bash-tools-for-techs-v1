# 🔧 Bash & PowerShell Tools for Field Technicians  
*Built by Wade Callender — AT&T Premises Technician | B.S. Cybersecurity*

This repository includes practical Bash and PowerShell scripts I’ve created or customized based on real-world challenges faced in the field as a Premises Technician at AT&T. These tools improve service workflows, support troubleshooting, and promote safety and documentation standards in dynamic and high-pressure environments.

As someone who recently earned a B.S. in Cybersecurity and has a decade of frontline experience in emergency services and telecom, this repo bridges hands-on knowledge with growing technical expertise.

---

## 🧰 Script Categories

### 🖧 NETWORK DIAGNOSTICS
| Script | Description |
|--------|-------------|
| `ping_sweep.sh` | Sweep an entire subnet to identify active devices — useful during installs or post-repair validation. |
| `trace_route.sh` | Trace packet paths for diagnosing slow connections or upstream ISP issues. |
| `dns_lookup.sh` | Quickly test domain resolution from a local device — great for DNS troubleshooting. |

---

### 📋 INVENTORY & LOGGING
| Script | Description |
|--------|-------------|
| `device_inventory.sh` | Automatically log MAC/IP/device data from connected clients to support recordkeeping or handoff. |
| `save_config.sh` | Capture and save current network settings as a snapshot during service or diagnostic visits. |

---

### 🔌 CONNECTIVITY MANAGEMENT
| Script | Description |
|--------|-------------|
| `restart_network.sh` | Restart network interface on Linux-based equipment in customer environments. |
| `flush_dns.ps1` | Windows PowerShell tool to clear DNS cache — resolves intermittent resolution failures. |

---

### 🔐 SECURITY & AWARENESS TOOLS
| Script | Description |
|--------|-------------|
| `port_scan.sh` | Internal port scanner using `nmap` to identify exposed services. Ideal for home network hardening. |
| `wifi_audit.sh` | List all devices connected to a router — supports spotting rogue clients or guest overuse. |

---

## 🦺 Safety, Privacy & Professionalism

**AT&T's culture of safety, compliance, and customer trust** is at the core of how I use and share these tools. All scripts are designed to:

- ⚠️ **Avoid storing or exposing customer credentials**
- ✅ Support **OSHA and AT&T ladder & PPE safety standards** (especially when tied to on-prem work)
- 🔐 Reinforce **data privacy** and best practices in the field
- 🧾 Support clean documentation, traceability, and escalation to network engineers

I’ve also incorporated principles from cybersecurity coursework — including risk-based thinking and root cause analysis — into how I design these tools.

---

## 💼 Use Cases

These tools were inspired by real tasks I’ve encountered:
- Fiber optic installs requiring rapid device discovery
- IP conflicts or dropped routes between gateway and ONT
- Latency issues from improperly configured DNS servers
- Verifying resolution after pole climbs or outdoor splicing
- Customer education on secure Wi-Fi practices

---

## 🧠 About Me

**Wade Callender**  
📍 Dallas, TX  
🎓 B.S. Cybersecurity – SNHU, Class of 2025  
💼 Premises Technician – AT&T (2023–Present)  
🩺 Former EMT – 10+ years of field response and incident management  
🧰 Cybersecurity Projects – OpenVAS, Packet Tracer, NIST audit playbooks  
📸 Creative Work – Owner of *Everyday Frames*, photography brand & visual storyteller

I bring a unique blend of customer-facing experience, hands-on fieldwork, and technical growth into everything I build. These scripts are a reflection of that journey.

---

## 📈 Planned Additions
- `arp_monitor.sh` – Track new MACs on the network to detect rogue devices
- `network_baseline_logger.sh` – Snapshot before/after states during service calls
- `remote_toolkit.ps1` – Common PowerShell commands for remote support

---

## 🤝 Contributions Welcome

If you're a field tech, helpdesk specialist, or student — feel free to fork, clone, or suggest additions.  
If you’re from AT&T and want a tailored version for your team, let’s connect.

Stay safe, document everything, and script with purpose 👷🏽‍♂️📡
