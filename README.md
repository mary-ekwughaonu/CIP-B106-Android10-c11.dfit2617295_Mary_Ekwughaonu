# CIP-B106 Mobile and IoT Forensics  
## Android 10 Pixel 3 Case Study

**Student:** Mary Ekwughaonu  
**Registration Number:** c11.dfit2617295  
**Case Identifier:** CIPB106-Android10-c11.dfit2617295  
**Submission Date:** October 2026  

---

### Case Overview

Forensic examination of a Google Pixel 3 running Android 10 (logical copy acquired after TWRP root access).  

The examination reconstructed:
- Device and account profile
- Installed applications and usage
- Native communications (SMS, Calls, Calendar)
- Third-party messaging applications (WhatsApp, TextNow, Kik)
- A supported chronology of activity (January–February 2020)

---

### Key Findings

| Finding | Detail |
|---------|--------|
| Device | Google Pixel 3 (codename: **blueline**) |
| OS | Android 10 (SDK 29, Build QQ1A.200105.003) |
| Security Patch | 2020-01-01 |
| Primary Google Account | thisisdfir@gmail.com |
| Users | User 0 (Primary), User 11 (Secondary) |
| Notable Apps | WhatsApp, Telegram, TextNow, Kik, Signal, Viber, Skype, Instagram, etc. |
| Key Activity Window | 29 January – 9 February 2020 |

---

### Evidence Integrity

| File | Algorithm | Hash |
|------|-----------|------|
| Pixel 3.zip | MD5 | `9cc37ebbbc4e918ee5427de1fe1deecc` |
| Pixel 3.zip | SHA-256 | `ca6918ef8b20486b6a5ded15609ac51318f377829480f93be3ba15364a8aa00a` |

The SHA-256 value matches the expected integrity value published in the course material.

---

### Repository Contents

---

### Tools Used

- Kali Linux
- `sqlite3`, `find`, `grep`, `cat`
- `sha256sum` / `md5sum`
- Manual review of SQLite databases and `build.prop` files

---

### Important Limitations

- The evidence is a **logical copy** acquired after TWRP root access. This does **not** prove that the original device user rooted the handset.
- Some artefacts (full Google Maps/Photos data, complete Wi-Fi SSIDs, full calendar titles) were not comprehensively recovered within the examination window.
- All conclusions are limited to what the supplied extraction can demonstrably support.

---

### Academic Integrity

This work was performed solely on the authorised course evidence.  
All findings are based on artefacts recovered from the supplied Pixel 3 Android 10 logical copy.

---

### Disclaimer

Training material only. Not related to any real investigation or real individuals.
