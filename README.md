# F5 Distributed Cloud DNS - Lab Guide Series

<p align="center">
  <img src="https://img.shields.io/badge/F5-Distributed%20Cloud-red?style=for-the-badge&logo=f5&logoColor=white" alt="F5 Distributed Cloud">
  <img src="https://img.shields.io/badge/DNS-Training%20Labs-blue?style=for-the-badge" alt="DNS Training">
  <img src="https://img.shields.io/badge/Labs-3%20Available-green?style=for-the-badge" alt="3 Labs">
</p>

## 📋 Overview

This repository contains comprehensive hands-on lab guides for **F5 Distributed Cloud DNS Training**. Learn how to leverage F5 XC DNS for high availability, DDoS protection, and secure DNS architecture.

| Item | Details |
|------|---------|
| **Course** | F5 Distributed Cloud DNS Training |
| **Lab Environment** | Kasm Workspaces (Container Streaming Platform) |
| **UDF Environment** | xc-dns-lab-v1 |
| **Requirements** | NO LIVE TENANT REQUIRED |

---

## 🔬 Lab Series

| Lab | Topic | Description | Duration |
|-----|-------|-------------|----------|
| [**Lab 1**](lab1/) | DNS Availability | Eliminate single-provider DNS dependency using F5 XC DNS as a dual primary provider | ~25 min |
| [**Lab 2**](lab2/) | Attack Mitigation | XC DNS absorbs DDoS attacks — watch a live DNS flood get mitigated in real time | ~30 min |
| [**Lab 3**](lab3/) | Hidden Primary | Hide BIND behind XC DNS for maximum protection — attackers can't target what they can't find | ~30 min |

---

## 📚 Lab Details

### Lab 1 — DNS Availability
> **Objective:** Eliminate single-provider DNS dependency using F5 Distributed Cloud DNS as a dual primary provider.

**What You'll Learn:**
- ✅ Verify baseline DNS configuration with Legacy BIND
- ✅ Simulate DNS provider outage and observe impact
- ✅ Create DNS zone in F5 XC Console
- ✅ Configure NS delegation at Registrar
- ✅ Implement dual primary DNS architecture

📖 [View Lab 1 Guide](lab1/F5_XC_DNS_Lab_Guide.md) | 📄 [PDF Version](lab1/F5_XC_DNS_Lab_Guide.pdf)

---

### Lab 2 — Attack Mitigation
> **Objective:** Demonstrate how XC DNS absorbs DDoS attacks while Legacy BIND would be overwhelmed.

**What You'll Learn:**
- ✅ Monitor healthy DNS baseline
- ✅ Launch simulated DNS flood attack
- ✅ Observe attack impact on infrastructure
- ✅ See XC DNS absorb and mitigate the attack
- ✅ Verify service continuity during attack

📖 [View Lab 2 Guide](lab2/F5_XC_DNS_Lab2_Attack_Mitigation_Guide.md) | 📄 [PDF Version](lab2/F5_XC_DNS_Lab2_Attack_Mitigation_Guide.pdf)

---

### Lab 3 — Hidden Primary
> **Objective:** Implement hidden primary architecture where BIND is completely invisible to attackers.

**What You'll Learn:**
- ✅ Understand hidden primary DNS architecture
- ✅ Configure zone transfer (AXFR) from BIND to XC DNS
- ✅ Remove BIND NS records from public delegation
- ✅ Verify automatic zone synchronization
- ✅ Test attack resilience with hidden primary

📖 [View Lab 3 Guide](lab3/F5_XC_DNS_Lab3_Hidden_Primary_Guide.md) | 📄 [PDF Version](lab3/F5_XC_DNS_Lab3_Hidden_Primary_Guide.pdf)

---

## 🏗️ Repository Structure

```
f5-xc-dns-lab-guide/
├── README.md                 # This file
├── lab1/                     # Lab 1: DNS Availability
│   ├── F5_XC_DNS_Lab_Guide.md
│   ├── F5_XC_DNS_Lab_Guide.pdf
│   └── step*.png             # Step-by-step screenshots
├── lab2/                     # Lab 2: Attack Mitigation
│   ├── F5_XC_DNS_Lab2_Attack_Mitigation_Guide.md
│   ├── F5_XC_DNS_Lab2_Attack_Mitigation_Guide.pdf
│   └── step*.png             # Step-by-step screenshots
└── lab3/                     # Lab 3: Hidden Primary
    ├── F5_XC_DNS_Lab3_Hidden_Primary_Guide.md
    ├── F5_XC_DNS_Lab3_Hidden_Primary_Guide.pdf
    └── step*.png             # Step-by-step screenshots
```

---

## 💡 Why No Live Tenant Required?

This lab uses a **fully simulated F5 XC DNS environment** that provides the same hands-on experience as a live tenant:

| Feature | Benefit |
|---------|---------|
| 🖥️ **Realistic XC Console Interface** | Learn the real workflow and navigation |
| 🌐 **Simulated DNS Infrastructure** | All operations behave exactly like production |
| 🔒 **Safe Learning Environment** | Make mistakes without affecting real infrastructure |
| ⚡ **No Account Setup Required** | Jump straight into learning |
| 🎯 **Consistent Experience** | Every participant gets the same pre-configured environment |

---

## 🔒 Lab Progression

Labs are designed to be completed **sequentially**. Each lab builds upon the configuration and knowledge from the previous lab:

```
Lab 1 (DNS Availability)
    │
    ▼ Requires dual primary setup
Lab 2 (Attack Mitigation)
    │
    ▼ Requires understanding of availability + mitigation
Lab 3 (Hidden Primary)
```

> **💡 Tip:** Complete Lab 1 first, then Lab 2 and Lab 3 will automatically unlock.

---

## 🛠️ Prerequisites

- Modern web browser (Chrome recommended)
- Access to Kasm Workspaces environment
- Credentials provided by your instructor

---

## 📞 Support

If you encounter any issues during the lab, please contact your instructor.

---

## 📝 License

This training material is provided for educational purposes as part of F5 Distributed Cloud DNS Training.

---

<p align="center">
  <b>Created for F5 Distributed Cloud DNS Training</b><br>
  Lab Guide Version 1.0
</p>
