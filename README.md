# Linux File System by Aryan

This note explains the core Linux file system in a simple, step-by-step way.

---

## 1. The Root (`/`)
- The root (`/`) is the top-level directory where everything starts. Think of it like the trunk of a tree.

---

## 2. Key Directories – What Goes Where

| Directory      | Purpose (Easy Description)                   |
|----------------|----------------------------------------------|
| `/bin`         | Basic tools needed for booting and fixing things |
| `/sbin`        | System tools—usually for the root user only   |
| `/lib`         | Shared code (libraries) for programs to use   |
| `/etc`         | System-wide configuration settings            |
| `/home`        | Personal folders for users                    |
| `/boot`        | Files needed to start (boot) your system      |
| `/dev`, `/proc`, `/sys`, `/run` | Special “virtual” folders showing live system info |
| `/usr`         | Non-essential programs and files (apps for users) |
| `/opt`         | Extra software you may add manually           |
| `/var`         | Files that change often (logs, emails, caches)|
| `/tmp`         | Temporary files (usually wiped after reboot)  |
| `/media`, `/mnt` | Where external drives (like USBs) are attached |
| `/srv`         | Data served by your system, like web files    |

---

## 3. What’s a Virtual Filesystem?
- Some directories (`/proc`, `/sys`, `/dev`, `/run`) don’t store real files—they show what's happening in your system right now. They live in memory and change as your system runs.

---

## Why It Matters
Knowing this layout helps you:
- Find files quickly
- Navigate confidently
- Keep your Linux system stable and safe

---

## Fast Memory Aid
- **Root (`/`)** is the trunk.
- **`/home`** = your personal space.
- **`/etc`** = settings.
- **`/usr`** = user programs.
- **Virtual dirs** = live system inside your OS.

---

Happy learning! This structure will stick with you now—in a simple and useful way.  
