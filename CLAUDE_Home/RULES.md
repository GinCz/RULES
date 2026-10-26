# 🟣 CLAUDE Home Master Rules (`AI/CLAUDE_Home/RULES.md`)
> **Personalized Profile for Claude AI Desktop & Web Models in Home Workstation Environment — Step 2**
> 
> *Repository:* [Secret_Privat ↗](https://github.com/GinCz/Secret_Privat) | *Owner:* Vladimir Bulantsev (GinCz)

---

## 🏗️ Execution Chain (Two-Step Rules Chain)
1. ⭐️ **Step 1 (Mandatory Base):** Always obey base rules in [`AI/01 - Mandatory rules for all AI/RULES.md ↗`](../01%20-%20Mandatory%20rules%20for%20all%20AI/RULES.md).
2. 🎯 **Step 2 (This File):** Home workstation environment settings `D:\AI\CLAUDE\`.

---

## 🏠 Home Environment & Sandbox (`D:\AI\CLAUDE\`)
1. **Claude Home Workspace:** All working files, temporary scripts, and artifacts MUST live strictly inside `D:\AI\CLAUDE\`.
2. **Shared Base Knowledge (`D:\AI\GitHub\Secret_Privat\`):** Read documentation from `D:\AI\GitHub\Secret_Privat\` using sitemap `D:\AI\GitHub\Secret_Privat\INDEX.md`.
3. **No Root Pollution:** Do not create files in the root of `D:\` or in other engines' folders.

---

## 🛑 Windows 11 Anti-Hang & Auto-Timeout Mandate
1. **SSH Network Timeouts:** Use `ssh -o BatchMode=yes -o ConnectTimeout=5 -o ServerAliveInterval=5 -o ServerAliveCountMax=1 -i ~/.ssh/id_ed25519 root@<IP> "<command>"`.
2. **Pre-Response Task Audit:** Run `manage_task(Action='list')` and terminate lingering background tasks via `manage_task(Action='kill')`.

---

## ⏱️ Single-Line Status Footer
`✅ Done: Started HH:MM:SS • Finished HH:MM:SS • Total: HH:MM:SS (Tokens: ~XXXX response / ~YYYY session)`
