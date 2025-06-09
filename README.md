# SoloWoW - SPP Vanilla Edition

Fully offline, self-hosted Vanilla WoW single-player setup using SPP_Server with tweaks:
- Anti-AFK addon
- Realmlist configured to `127.0.0.1`
- No intro cinematics
- Tweaked client with ambient sound in background

## 🛠 How to Run
1. Launch `mangosd.exe` and `realmd.exe` inside `SPP_Server`
2. Run `WoW.exe`
3. Login with `admin / admin`

## ✏ Notes
- This repo is for **personal ambient or study use**
- Addons are in `Interface/AddOns`
- Backups and temporary files are ignored by `.gitignore`

## 📌 Terminal Setup Commands

1. Install Git LFS (Large File Support)
git lfs install

2. Clone the Repo (if you prefer that over unzipping the folder)
git clone https://github.com/KazuhiraSet/SoloWoW.git
cd SoloWoW

3. Fetch Large Files
git lfs pull

## 🔗 External Downloads (Required Files)

Due to GitHub's file size restrictions, some essential files must be downloaded manually and placed into the correct folders.

---

### 📁 SPPE.exe  
**Download Link:**  
[SPPE.exe (Google Drive)](https://drive.google.com/file/d/16pMa-WSeSpomYqpfWt-G8GbMqAf63tf7/view?usp=drive_link)

**Place this file into:**  
`SPP_Server/Server/Tools/`

---

### 📁 mangosd.pdb (Vanilla Version)  
**Download Link:**  
[mangosd.pdb (Google Drive)](https://drive.google.com/file/d/1s6_U7zH4j0lADG0aKh-9sNQzvKCnr1PM/view?usp=drive_link)

**Place this file into:**  
`SPP_Server/Settings/vanilla/`

---

> ⚠️ **Important:** These files are required for proper server functionality. They are not stored on GitHub due to size limits. Without these files in place, some components may not launch correctly or may display errors.



> ⚠️ If `Wow.exe` is missing after downloading ZIP, download it separately:
> [Download WoW.exe (external link)](https://drive.google.com/file/d/1O49pk5oBGJW6TKJoiCKUp9dnBSvV4zST/view)

And copy/paste all the files in the folder where WoW.exe is into SPP_Classics_V2 > SPP_Server > Server > Binaries > vanilla > Bin64

🧪 To Start the Game:
1. Run Server_Update (for the first time only, follow the instructions), then run Server_Start.bat, which will run `SPP_Server/mangosd.exe` and `SPP_Server/realmd.exe` - DO NOT close this, keep it running in the background as long as you play.
2. Launch `WoW.exe` (found in `Bin64/`)
3. Login: `admin / admin`

ENJOY!