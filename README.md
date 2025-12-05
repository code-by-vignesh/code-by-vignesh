<!--
**code-by-vignesh/code-by-vignesh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!--
<div align="center">

# Hi there, I'm Vigneshkumar S 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2F88FF&width=435&lines=Network+Automation+Engineer;Multi-Vendor+Automation+(Cisco%2FJuniper);ZTP+%26+OS+Upgrade+Specialist;Building+Scalable+Network+Infra)](https://git.io/typing-svg)

<br/>

<p align="center">
 <b>Network Automation Engineer</b> specializing in End-to-End Device Lifecycle Management.<br/>
 I build production-grade automation engines that handle everything from <b>Zero Touch Provisioning (ZTP)</b> to <b>Automated OS Upgrades</b> and Compliance for Juniper & Cisco networks.
</p>

<a href="#">
  <img src="https://img.shields.io/badge/Certification_Goal-JNCIA--Junos_(In_Progress)-orange?style=for-the-badge&logo=juniper-networks&logoColor=white"/>
</a>

<br/><br/>

</div>

---

### 🚀 Core Automation Architecture

I have developed and deployed complete automation workflows for both **Juniper (MX/EX)** and **Cisco (IOS/IOS-XE)** platforms.

#### 1️⃣ Full-Cycle Device Automation (Day 0 to Day N)
*Engineered a vendor-agnostic framework using Python & Ansible.*

* **⚡ Day 0: Zero Touch Provisioning (ZTP)**
    * Automated the onboarding of bare-metal devices.
    * **Juniper:** Auto-provisioning via DHCP options and Python scripts.
    * **Cisco:** Automated initial config injection during boot process.
* **🔄 OS Management:**
    * Built safe workflows for **Automated OS/Firmware Upgrades**.
    * Includes pre-checks, image validation, and post-upgrade verification.
* **⚙️ Config Operations (Push/Pull):**
    * **Push:** Bulk configuration deployment (ACLs, VLANs, User specifics) using **Paramiko** and **Netmiko**.
    * **Pull:** Automated state auditing and drift detection.
* **🛡️ Disaster Recovery:**
    * Automated daily **Backup** of running-configurations to version control systems.

#### 2️⃣ Advanced Network Observability
*Built a custom telemetry stack to monitor critical network health parameters.*

* **Stack:** Prometheus, SNMP Exporter, Grafana, Docker Compose.
* **Deep-Dive Metrics Strategy:**
    * ✅ **Device Health:** System Uptime, Inventory (Serial Numbers), and Hardware Details.
    * ✅ **Interface Telemetry:** Real-time monitoring of Traffic, Errors (CRC), and Discards (Buffer overflows).
    * ✅ **Security:** Tracking TCP/UDP connection counts to detect anomalies.
* *Note on Resource Monitoring:* Implemented specific OID polling for Interface metrics while avoiding generic CPU OIDs to ensure multi-vendor compatibility.

---

### 🛠 Technical Arsenal

<div align="center">

| **Network Platforms** | **Automation & Code** | **Tools & Infrastructure** |
|:---:|:---:|:---:|
| ![Juniper](https://img.shields.io/badge/Juniper-MX_%2F_EX-Black?style=flat-square&logo=juniper-networks&logoColor=white) | ![Python](https://img.shields.io/badge/Python_(Paramiko%2FNetmiko)-3776AB?style=flat-square&logo=python&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) |
| ![Cisco](https://img.shields.io/badge/Cisco-IOS_%2F_XE-1BA0D7?style=flat-square&logo=cisco&logoColor=white) | ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Routing (BGP/OSPF)** | **Bash Scripting** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) |
| **Switching (STP/VLAN)** | **Jinja2 Templating** | **Git / GitHub** |

</div>

---
<!--
### 📊 GitHub Activity

<div align="center">

<a href="https://github.com/CHANGE_THIS_TO_YOUR_USERNAME">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=CHANGE_THIS_TO_YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CHANGE_THIS_TO_YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true"/>
</a>

</div>

<br/>

<div align="center">
<a href="https://www.linkedin.com/in/s-vigneshkumar-be/">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
</div>
-->
<!--

<div align="center">

# Hi there, I'm Vigneshkumar S 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2F88FF&width=435&lines=Network+Automation+Engineer;Orchestrating+Workflows+with+Jenkins;ZTP+%26+Python+Automation;Building+Self-Service+Network+Portals)](https://git.io/typing-svg)

<br/>

<p align="center">
 <b>Network Automation Engineer</b> bridging the gap between Web UI and Network Infrastructure.<br/>
 I build <b>Event-Driven Automation Pipelines</b> where Jenkins acts as the orchestration engine to trigger backend Python scripts for ZTP, Config Pushes, and Compliance Audits.
</p>

<a href="#">
  <img src="https://img.shields.io/badge/Certification_Goal-JNCIA--Junos_(In_Progress)-orange?style=for-the-badge&logo=juniper-networks&logoColor=white"/>
</a>

<br/><br/>

</div>

---

### 🚀 Automation Architecture & Workflows

My core expertise lies in decoupling the "Trigger" from the "Execution," allowing for a modular and scalable automation architecture.

#### 1️⃣ The Orchestration Layer (Jenkins as Middleware)
*Built a "Click-to-Config" pipeline integrating Frontend UI with Backend Logic.*
* **The Workflow:** Frontend Trigger ➔ **Jenkins Webhook** ➔ Python/Ansible Worker ➔ Network Device.
* **Role of Jenkins:** Acts as the central execution engine to sanitize inputs and trigger isolated build jobs for configuration changes.
* **Result:** Enables non-technical users to perform complex network changes securely via UI without touching the CLI.

#### 2️⃣ Full-Cycle Device Automation (Backend Engine)
*Engineered the core logic using Python & Ansible for Juniper (MX/EX) & Cisco (IOS).*
* **⚡ Zero Touch Provisioning (ZTP):** Automated "Day 0" onboarding of bare-metal devices via DHCP options.
* **🔄 OS Management:** Automated Firmware Upgrades with pre/post-check validation logic.
* **⚙️ Config Operations:**
    * **Push:** Bulk config deployment using **Paramiko** (SSH) & **Netmiko**.
    * **Pull:** Automated state auditing and configuration backup.

#### 3️⃣ Advanced Network Observability
*Built a custom telemetry stack for real-time monitoring.*
* **Stack:** Prometheus, SNMP Exporter, Grafana, Docker Compose.
* **Key Metrics Strategy:**
    * ✅ **Interface Telemetry:** Monitoring Traffic, CRC Errors, and Buffer Discards.
    * ✅ **Device Health:** Tracking System Uptime and Inventory (Serial Numbers) via OIDs.
    * ✅ **Security:** TCP/UDP connection tracking to detect anomalies.

---

### 🛠 Technical Arsenal

<div align="center">

| **Orchestration & CI/CD** | **Automation & Code** | **Infra & Monitoring** |
|:---:|:---:|:---:|
| ![Jenkins](https://img.shields.io/badge/Jenkins-Orchestrator-D24939?style=flat-square&logo=jenkins&logoColor=white) | ![Python](https://img.shields.io/badge/Python_(Backend)-3776AB?style=flat-square&logo=python&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) |
| ![Ansible](https://img.shields.io/badge/Ansible-Playbooks-EE0000?style=flat-square&logo=ansible&logoColor=white) | ![Bash](https://img.shields.io/badge/Bash_Scripting-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) | ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Webhooks / API** | **Jinja2 Templating** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) |
| **Git Version Control** | **Paramiko / Netmiko** | **Juniper & Cisco** |

</div>

---

### 📊 GitHub Activity

<div align="center">

<a href="https://github.com/CHANGE_THIS_TO_YOUR_USERNAME">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=CHANGE_THIS_TO_YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CHANGE_THIS_TO_YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true"/>
</a>

</div>

<br/>

<div align="center">
<a href="https://www.linkedin.com/in/s-vigneshkumar-be/">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
</div>

-->

<div align="center">

# Hi there, I'm Vigneshkumar S 👋

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2F88FF&width=435&lines=Network+Automation+Engineer;NetDevOps+%26+Orchestration;Python+%7C+Ansible+%7C+Jenkins;Juniper+%26+Cisco+Specialist)](https://git.io/typing-svg)

<br/>

<p align="center">
 <b>Network Automation Engineer</b> specializing in building self-service network portals and observability stacks.<br/>
 I connect <b>Web UIs</b> to <b>Network Infrastructure</b> using Jenkins and Python to automate ZTP, OS Upgrades, and Compliance.
</p>

<a href="#">
  <img src="https://img.shields.io/badge/Certification_Goal-JNCIA--Junos_(In_Progress)-orange?style=for-the-badge&logo=juniper-networks&logoColor=white"/>
</a>

<br/><br/>

</div>

---

### 🚀 Key Projects

#### 1️⃣ Event-Driven Network Automation
*Bridging the gap between Frontend UI and Backend Network Configs.*
* **Orchestration:** Built a pipeline where **Jenkins** acts as the middleware to trigger Python scripts based on User Actions.
* **Scope:** Handles **Zero Touch Provisioning (ZTP)**, Firmware Upgrades, and Bulk Config Pushes for Juniper & Cisco.
* **Tech:** Jenkins Webhooks, Python (Paramiko/Netmiko), Ansible.

#### 2️⃣ Full-Stack Network Observability
*A vendor-agnostic monitoring stack for real-time network insights.*
* **Traffic & Health:** Visualized high-speed Interface Traffic, Error Rates (CRC/Discards), and System Uptime.
* **Security:** Implemented **TCP/UDP Connection Tracking** to identify potential traffic anomalies and flood attacks.
* **Design:** Built using **Docker Compose**, **Prometheus**, and **SNMP Exporter**, focusing on standard OIDs for multi-vendor compatibility.

---

### 🛠 Technical Arsenal

<div align="center">

| **Network Platforms** | **Automation & Code** | **Tools & Infrastructure** |
|:---:|:---:|:---:|
| ![Juniper](https://img.shields.io/badge/Juniper-MX_%2F_EX-Black?style=flat-square&logo=juniper-networks&logoColor=white) | ![Python](https://img.shields.io/badge/Python_(Paramiko,Netmiko)-3776AB?style=flat-square&logo=python&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) |
| ![Cisco](https://img.shields.io/badge/Cisco-IOS_%2F_XE-1BA0D7?style=flat-square&logo=cisco&logoColor=white) |![Ansible](https://img.shields.io/badge/Ansible-Playbooks-EE0000?style=flat-square&logo=ansible&logoColor=white) | ![Grafana](https://img.shields.io/badge/Grafana-Dashboard-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Routing** | ![Jenkins](https://img.shields.io/badge/Jenkins-Orchestrator-D24939?style=flat-square&logo=jenkins&logoColor=white) | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) |
| **Switching** | **Bash / Jinja2** | **Git / GitHub** |

</div>

---
<!--
### 📊 GitHub Activity

<p align="left">
  <i>(Graphs will appear here once code contributions begin...)</i>
</p>
-->
<br/>

<div align="center">
<a href="https://www.linkedin.com/in/s-vigneshkumar-be/">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
</div>
