---
layout: post
title: "Implementing Secure File Sharing for a Remote Team"
date: 2026-03-24
categories: [projects]
tags: [
  Microsoft365, SharePointOnline, OneDriveSync, GoDaddyTenant, CloudFileSharing,
  WindowsFileSync, MacFileSync, RoleBasedAccessControl, FolderPermissions,
  DNSVerification, CrossPlatformAccess, RemoteWorkIT, SecureCollaboration,
  EnterpriseFileManagement, FileStructureDesign, EndUserDocumentation
]
excerpt: "Designed and deployed a secure, cloud-based file sharing system for a fully remote business, replacing a proposed VPN solution with a more scalable and reliable SharePoint architecture."
---

## Overview

I designed and implemented a secure, cloud-based file sharing system for a small business with a fully remote team. The goal was to replace ad-hoc file sharing and a proposed VPN solution with a centralized, scalable, and secure SharePoint environment that works across Windows and macOS devices.

---

## Objectives

- Provide a centralized location for company files  
- Enable secure access for remote employees  
- Implement role-based access control for sensitive data  
- Ensure compatibility across Windows and Mac systems  
- Avoid disruption to existing email infrastructure  

---

## Challenges

- The organization had no centralized file system  
- Employees worked fully remotely with no internal network  
- Existing domain (`immnow.com`) was tied to a GoDaddy-managed Microsoft 365 tenant  
- Needed to avoid disrupting existing email services  
- Mixed operating system environment (Windows + Mac)  

---

## Solution

I implemented a SharePoint-based solution within the existing Microsoft 365 tenant. The approach avoided VPNs, minimized risk to existing systems, and allowed seamless cross-platform access.

### Steps Taken

1. **Tenant Assessment**
   - Verified existing Microsoft 365 tenant via GoDaddy
   - Confirmed domain verification and current email setup
2. **User Setup**
   - Created employee accounts in Microsoft 365 for SharePoint access
   - Assigned role-based permissions
3. **SharePoint Site Creation**
   - Created a SharePoint Team Site named **Company Files**
   - Built folder structure for business operations
4. **Folder Permissions**
   - Restricted sensitive folders (Finance, HR) to specific employees
   - Enabled read/write access only where appropriate
5. **File Sync**
   - Configured OneDrive Sync for Windows and Mac
   - Trained employees to sync and organize files locally
6. **Documentation**
   - Created step-by-step guide for employees

---

## Security Considerations

- Avoided exposing internal systems via VPN  
- Implemented least-privilege access controls  
- Prevented disruption to existing email services  
- Configured cross-platform sync securely  

---

## Results

- Centralized file storage accessible to all remote employees  
- Secure access for sensitive data  
- Seamless cross-platform synchronization  
- Clear folder organization and documentation  
- Eliminated the need for a VPN while maintaining security  

---

## Lessons Learned

- Cloud-based file sharing can be simpler, more reliable, and easier to manage than VPN solutions  
- Understanding the existing IT environment is critical to prevent downtime  
- Clear documentation ensures employee adoption and minimizes support requests  
- Role-based access control is essential for protecting sensitive business data  

---

## Future Improvements

- Implement multi-factor authentication for all accounts  
- Migrate company email fully into Microsoft 365 for centralized management  
- Set up automated backups and retention policies  
- Monitor SharePoint access for auditing and compliance  

---

## Technologies Used

- Microsoft 365  
- SharePoint Online  
- OneDrive Sync Client  
- GoDaddy-managed tenant  
- Windows and macOS file sync  

---

> This project demonstrates my ability to design and deploy practical IT solutions for real-world business needs, balancing security, usability, and risk mitigation.