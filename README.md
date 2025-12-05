# Disclaimer
Use these tools at your own risk. Always test in a development environment before deploying to production.

# macOS Endpoint Management Toolkit

This repository documents tools and workflows I use as an Endpoint Management Technician for managing MacBooks. It includes packaging, signing, compliance, and configuration utilities.

---

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

---

## 📄 Profile Management
- **iMazing Profile Editor**  
  - https://imazing.com/blog/introducing-imazing-profile-editor  
  - **Use Case:** Inspect and edit Apple Configuration Profiles.

