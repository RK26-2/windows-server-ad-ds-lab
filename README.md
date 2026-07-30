**🚀 Windows Server AD DS Deployment & Identity Management Lab**

An enterprise-focused home lab project demonstrating the setup, configuration, and troubleshooting of a Windows Server Domain Controller and Active Directory Domain Services (AD DS) environment.

**📌 Project Overview**

This project highlights the end-to-end implementation of an isolated identity management infrastructure (lab.local). It covers overcoming network interface binding challenges, configuring self-referential DNS bindings, automating administrative tool deployments via PowerShell CLI, and managing directory objects.


**🛠️ Tech Stack & Skills Highlighted**

**OS: Windows Server**

**Services**: Active Directory Domain Services (AD DS), DNS Architecture, NetBIOS

**Networking**: Microsoft Loopback Adapter, Static IPv4 Binding (192.168.1.10), Loopback Resolution (127.0.0.1)

**Administration**: PowerShell CLI, Remote Server Administration Tools (RSAT), MMC Snap-ins (dsa.msc)

**Troubleshooting**: Network adapter binding resolution, credential policies, DSRM setup


**🏗️ Architecture & Implementation Highlights**

1. Network Adapter & DNS Configuration
Resolved physical disconnect issues in an isolated virtual/physical lab environment by configuring a Microsoft KM-TEST Loopback Adapter with self-referential DNS settings for domain stability.

2. AD DS & Domain Controller Promotion
Promoted local server DC-01 to a Primary Domain Controller for the lab.local root domain.

3. CLI Management & RSAT Provisioning
Automated the installation of Active Directory Remote Server Administration Tools via administrative PowerShell:

                     Install-WindowsFeature -Name RSAT-ADDS

5. User Directory & Object Management
Structured domain Organizational Units (OUs) and provisioned domain user accounts (lab.local\testuser) with custom complexity and password policies.

**📂 Repository Contents**
[Lab_Report.pdf](AD-DS-Infrastructure-Lab.pdf) - Comprehensive technical documentation featuring step-by-step walk-throughs, troubleshooting takeaways, and executive summaries.

**📂[screenshots](screenshots/)** - Visual proof of network adapter configurations, PowerShell commands, and active MMC snap-ins (dsa.msc).
