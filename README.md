# Nomad Automata ⚙️

A collection of pragmatic, zero-bullshit PowerShell automation scripts for digital nomads and wasteland wanderers. 
Keep your system clean, your data safe, and your mind focused.

## 🧹 Wasteland Sweeper
A smart cleaner for your Downloads folder. 
- Deletes files older than 14 days.
- **Safe by design:** Ignores `.exe`, `.iso`, `.zip`, `.rar`, `.pdf`.
- Ignores any file with `[KEEP]` in the name.
- Supports `-DryRun` mode to check what would be deleted without actually touching the files.

**Usage:**
```powershell
.\Wasteland_Sweeper\sweeper.ps1 -DryRun
```

## 🛡️ Oasis Backup
A robust backup script for Obsidian Vaults or any knowledge base.
- Creates timestamped `.zip` archives locally.
- Automatically syncs the latest backups to the cloud using `rclone`.

**Usage:**
```powershell
.\Oasis_Backup\backup_oasis.ps1
```

---
**Made by Makaric & The AI Tandem**