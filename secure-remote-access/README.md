Secure Remote Access with Azure VPN + Entra ID

## Objective
1. Enforce VPN-only access to resources
2. Eliminate public exposure

## Implementation
1. Configured Azure VPN Gateway (Point-to-Site).  
2. Integrated Entra ID authentication.  
3. Applied NSG rules to block direct access and provide network segmentation.  
4. Verified connectivity with private IP via VPN.  

## Outcome
- Public access removed.  
- Users now authenticate securely with MFA + VPN.  
- Defender for Cloud confirmed risk of public access resolved.  

## Screenshots & Diagrams
To add screenshots, Azure portal captures, or architecture diagrams

Successful VPN Connection
<img width="919" height="740" alt="image" src="https://github.com/user-attachments/assets/48d97d14-743c-44b4-861a-6c87a8f990d8" />


## Skills Applied
- Azure Networking  
- Identity & Access Management  
- Microsoft Defender for Cloud 
