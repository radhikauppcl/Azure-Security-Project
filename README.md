# Azure-Security-Portfolio
End-to-end Azure security projects implementing VPN, Microsoft Defender, Conditional Access, and Zero Trust best practices.


##  Overview
This repository documents a series of major Azure security projects I am working on.  
The goal is to **secure cloud resources**, enforce **Zero Trust principles**, and integrate **Microsoft Defender and Azure AD** into practical enterprise-ready solutions.

---

##  Projects and Expected Outcomes

### 1. Secure Azure Resources with VPN + Azure AD(./secure-remote-access/) to ensure
- Eliminated public exposure  
- Configured Point-to-Site VPN with Azure AD authentication  
- Applied Microsoft Defender for Cloud recommendations  
- Enforced Conditional Access and endpoint compliance  

---

### 2. GitHub Repository Protection(link to project) to ensure
- Restricted access to sensitive repos via VPN-only  
- Applied Conditional Access policies  
- Integrated Defender for Endpoint on BYOD laptops  

---

### 3. Insider Threat & DLP Controls(link to project) to ensure
- Prevented data exfiltration from GitHub Codespaces  
- Applied Intune + Defender for Endpoint for device control  
- Used Conditional Access to restrict unmanaged devices  

---

##  Stack
- **Azure AD** (Identity & Access)  
- **Microsoft Defender for Cloud & Endpoint** (Threat protection)  
- **Azure VPN Gateway** (Secure remote access)  
- **Conditional Access** (Zero Trust enforcement)  
- **NSG & Firewall** (Network hardening)  
- **Intune** (Endpoint compliance & BYOD security)  

---

##  Skills Demonstrated

- Azure Networking (VNet, VPN Gateway, NSG)  
- Microsoft Entra ID (Azure AD) & Conditional Access  
- Microsoft Defender for Cloud & Endpoint  
- Endpoint Compliance with Intune  
- GitHub Enterprise Security Practices  
- Zero Trust Security Design

---

## Lessons Learned
- Importance of properly configuring **AAD app registrations** for VPN  
- NSG rules must explicitly allow **VPN-to-resource traffic**  
- **Conditional Access** is the glue for enforcing Zero Trust across Azure & SaaS  
- Defender provides visibility, but policies + configuration close the loop  

---

## Author
**Ofunneka Jennifer Okonkwoabutu — *Cybersecurity | Cloud Security | AI Security*  
- LinkedIn: [link]  
- GitHub Portfolio: *This repo is a living collection of my Azure security implementations*

