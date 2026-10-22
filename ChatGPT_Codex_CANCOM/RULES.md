# 🟢 ChatGPT Codex CANCOM Master Rules (`AI/ChatGPT_Codex_CANCOM/RULES.md`)
> **Personalized Profile for ChatGPT & OpenAI Codex in CANCOM Corporate Environment — Step 2**
> 
> *Repository:* [Secret_Privat ↗](https://github.com/GinCz/Secret_Privat) | *Owner:* Vladimir Bulantsev (GinCz)

---

## 🏗️ Execution Chain (Two-Step Rules Chain)
1. ⭐️ **Step 1 (Mandatory Base):** Always obey base rules in [`AI/01 - Mandatory rules for all AI/RULES.md ↗`](../01%20-%20Mandatory%20rules%20for%20all%20AI/RULES.md).
2. 🎯 **Step 2 (This File):** Corporate environment settings `C:\UTIL\Codex\` and `C:\CANCOM\`.

---

## 🏢 Shared CANCOM Database (`C:\CANCOM\`)
1. **Unified Hub for All 3 Engines:** Shared database on `C:\CANCOM\` continuously enriched by:
   - 🪐 **Antigravity AI** (`C:\UTIL\Antigravity_AI\`)
   - 🟣 **Claude** (`C:\UTIL\Claude\`)
   - 🟢 **ChatGPT Codex** (`C:\UTIL\Codex\`)
2. **STRICT APPEND-ONLY RULE:**
   - **ONLY ADD NEW DATA.**
   - **DELETING ANY FILES OR DATA FROM C:\CANCOM\ IS STRICTLY PROHIBITED.**
3. **Pure Text Format — Strict Ban on Binary Bloat (No Images, Screenshots, or PDFs):**
   - **NO binary files, images, screenshots, or PDF documents** in `C:\CANCOM\`.
   - All documents, tickets, attachments, and articles from Jira / Confluence / web MUST be immediately downloaded and converted/extracted to **pure text / markdown (`.md` / `.txt`)** upon first access.
   - This ensures instant indexing, lightning-fast text searches, and maximum token efficiency across all AI engines.
4. **Immediate Ticket & Knowledge Caching:**
   - Whenever work starts on a ticket or topic, immediately save its complete text representation in [`C:\CANCOM\tickets\` ↗](file:///C:/CANCOM/tickets/) or `C:\CANCOM\knowledge\`.
   - All subsequent lookups MUST read the local text cache rather than making repeated external network queries.
5. **Zero Passwords & KeePass Policy:**
   - Store usernames and KeePass record references only (e.g. `Username: v.bulantsev | KeePass: CANCOM/Jira_Admin`).
6. **Fast Router:** Read lightweight navigator [`C:\CANCOM\INDEX.md` ↗](file:///C:/CANCOM/INDEX.md) (< 50 lines) first.

---

## 🔒 Isolation & Workspace Rules (`C:\UTIL\Codex\`)
1. **Codex Workspace:** All working files and scripts MUST live strictly inside `C:\UTIL\Codex\`.
2. **Clean C:\UTIL Root:** Never leave files in the root of `C:\UTIL\`.
3. **Desktop Ban:** Never save files to `C:\Users\USER\Desktop\`.

---

## 🛑 Windows 11 Anti-Hang & Auto-Timeout Mandate
1. **SSH Network Timeouts:** Use `ssh -o BatchMode=yes -o ConnectTimeout=5 -o ServerAliveInterval=5 -o ServerAliveCountMax=1 -i ~/.ssh/id_ed25519 root@<IP> "<command>"`.
2. **Pre-Response Task Audit:** Run `manage_task(Action='list')` and terminate lingering background tasks via `manage_task(Action='kill')`.

---

## ⏱️ Single-Line Status Footer
`✅ Done: Started HH:MM:SS • Finished HH:MM:SS • Total: HH:MM:SS (Tokens: ~XXXX response / ~YYYY session)`
