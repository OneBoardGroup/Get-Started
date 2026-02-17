# Technical Requirements

This document describes the technical prerequisites and integration options for using the Oneboard platform on the customer side.

## 1. System Requirements

**End Devices**

- Operating system: Windows, Linux, MacOS, Docker
    
- Free storage space: at least 10 GB
    
- Internet connection: stable; the router may need to open ports for proxy usage

**Model**

- Simplest model: Local instance – no setup costs
- Windows-hosted model: VDI instance with open ports (4869, and for email: 993, 465) – low setup costs
- Linux-hosted model: Terraform and Docker for organization-wide unified installation or as-a-service – SaaS
    
**Browser**

- Google Chrome – latest version
    
- Required for the web-based dashboard and administrative functions
    

## 2. KYC Flow (End-Customer Onboarding)

**Integration**

- Simple embedding via a customer-specific link
    
- The link can be placed directly on the customer’s website (e.g. button or redirect) (see screenshot)
    
- No additional software installation required on the end-customer side
    

![Onboardinglink](https://github.com/OneBoardGroup/Get-Started/blob/main/Onboardinglink.png?raw=true)

## 3. Compliance Cockpit (Internal Use)

**Installation**

- Download of the Oneboard Node application as a local application on the customer’s computer
    
- Installation on Windows systems
    

**Security Architecture**

- Access to the Compliance Cockpit is local on the computer
    
- End-to-end encrypted data processing
    
- No direct cloud dependency for operational access
    
- Data storage according to individual architecture (local / own database / cloud)
    

**Network & Access**

- The Node can provide a proxy
    
- Via this proxy, the Compliance Cockpit can be enabled for all users within the same network
    
- Prerequisite:
    
    - Internal internet and security settings must allow the Node to create a proxy
        

**User Management**

- Each user creates an individual login
    
- Authentication is performed using:
    
    - Real name & biometric verification
        
- Every access is uniquely attributable to a specific person
    

## 4. Data Transfer & Interfaces

**Integration Options**

- Connection to internal systems as required, e.g.:
    
    - CRM, core banking systems, internal compliance or archiving systems
        
- Setup of:
    
    - Backup processes
        
    - Data exports (structured formats)
        

**Approach**

- Scope and type of interfaces are defined jointly in a technical alignment meeting
    
- A Terms & Conditions template is provided
    
- Targeted implementation and configuration follow thereafter
