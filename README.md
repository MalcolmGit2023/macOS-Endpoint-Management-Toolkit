# Disclaimer
Use these tools at your own risk. Always test in a development environment before deploying to production. I did not create any of the applications. Thank the developers for contributing these helpful applications.

# macOS Endpoint Management Toolkit

This repository documents tools and workflows I use as an Endpoint Management Technician for managing MacBooks. It includes packaging, signing, compliance, and configuration utilities.

---
## 🏷️ Repository Tags

`macos` `macadmin` `jamf` `mdm` `automation` `security` `compliance` `packaging` `scripting` `enterprise-it`

## 📦 Package Creation
- **Packages App**  
  - https://packages.macupdate.com/  
  - http://s.sudre.free.fr/Software/Packages/about.html  
  - **Use Case:** Combine binaries (e.g., https://github.com/scriptingosx/desktoppr), JPEG files, and scripts into a single deployable package for Jamf.
      - Take a dmg file and turn it into a pkg file.
---
   

## 🖼 Desktoppr 
  - https://github.com/scriptingosx/desktoppr  
  - **Use Case:** Set MacBook wallpaper via command line or deployment script.


---

## 🔏 Package Signing
- **Hancock**  
  - https://github.com/JeremyAgost/Hancock  
  - **Use Case:** Sign packages before deployment.

---

## ✅ Package Verification
- **Suspicious Package**  
  - https://mothersruin.com/software/SuspiciousPackage/get.html  
  - **Use Case:** Confirm package signatures and inspect contents.

---

## 🛡 Compliance & Benchmarks
- **Jamf Compliance Editor**  
  - https://github.com/Jamf-Concepts/jamf-compliance-editor  
  - **Use Case:** View CIS benchmarks, download plist, and import into Jamf.
 
### MACE Compliance Editor ✅ Production‑Used
https://github.com/GarySieling/MACEngine

---

### Installomator ✅ Production‑Used
Automated application installation and updating framework for macOS.

https://github.com/Installomator/Installomator

---

## 📄 Profile Management
- **iMazing Profile Editor**  
  - https://imazing.com/blog/introducing-imazing-profile-editor  
  - **Use Case:** Inspect and edit Apple Configuration Profiles.
 
---

## 🛠 Management & Automation

### SwiftDialog ✅ Production‑Used
https://github.com/swiftDialog/swiftDialog

### Jamf Helper ✅ Production‑Used
Included with Jamf Pro

### Setup Manager 🧪 Lab + Production
https://github.com/setup-manager/setup-manager

### Self Service+ ✅ Production‑Used
https://github.com/Self-Serviced/Self-Service-Plus

### AutoPkg / AutoPatch ✅ Production‑Used
https://github.com/autopkg/autopkg

---

## 🧑‍💻 Developer & Script Authoring

### Sublime Text ✅ Production‑Used
https://www.sublimetext.com

### Visual Studio Code ✅ Production‑Used
https://code.visualstudio.com

---

## 🤖 Automation & AI Assistance

### Microsoft Copilot ✅ Daily‑Used
Used for scripting and Jamf workflows (validation always required).

