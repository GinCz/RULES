# 🤖 Master AI Rules & Sandboxing Manifest (RULES)

> **Single Source of Truth for Universal AI Rules, Token Economy, and Environment Profiles**  
> *Repository:* [GinCz/RULES ↗](https://github.com/GinCz/RULES) | *Author:* [Vladimir Bulantsev (@GinCz)](https://github.com/GinCz) | *Version:* v2026-11

---

## 🏗️ Structure Overview

```text
RULES/
│
├── RULES.md                        <-- Master AI Rules & Routing Manifest
├── AGENTS.md                       <-- Multi-agent orchestration rules
├── TOKEN_ECONOMY.md                <-- Token economy & context management standards
│
├── 01 - Mandatory rules for all AI/ <-- Step 1: Universal rules for every model
├── Antigravity_Home/               <-- Step 2: Google Antigravity (Home PC) profile
├── Antigravity_CANCOM/             <-- Step 2: Antigravity (CANCOM Work) profile
├── ChatGPT_Codex_Home/             <-- Step 2: ChatGPT / Codex (Home PC) profile
├── ChatGPT_Codex_CANCOM/           <-- Step 2: ChatGPT / Codex (CANCOM Work) profile
├── CLAUDE_Home/                    <-- Step 2: Claude Desktop / Web (Home PC) profile
├── CLAUDE_CANCOM/                  <-- Step 2: Claude (CANCOM Work) profile
├── Copilot/                        <-- Step 2: GitHub Copilot profile
├── VS_Code/                        <-- Step 2: VS Code / Cursor profile
├── Perplexity/                     <-- Step 2: Perplexity search profile
└── Other_AI/                       <-- Step 2: Fallback profile for other models
```

---

## ⚡ Key Highlights & Architecture

1. **Deterministic Two-Step Rules Chain:**
   - **Step 1:** Mandatory baseline rules applied globally across all models (zero hallucination, strict single-task focus, turnkey execution).
   - **Step 2:** Environment-specific and model-specific profiles adapted for Antigravity, Claude, ChatGPT, Codex, and Cursor.
2. **Context & Token Economy:**
   - Slice-reading standards (`grep`, narrow line ranges).
   - Categorical ban on whole-file ingestion for files > 100 lines.
   - Internal calculation first (<= 1s arithmetic and date calculations without spawning CLI tools).
3. **Turnkey Autonomous Execution:**
   - Full agency to diagnose, write code, run tests, and commit without asking permission questions.
   - Strict audit stamping on every response.

---

## 🔄 Multi-Model Compatibility Matrix

| Model / Agent | Profile Directory | Status | Enforcement Standard |
| :--- | :--- | :---: | :--- |
| **Google Antigravity / Gemini** | `Antigravity_Home/`, `Antigravity_CANCOM/` | Active | Full CLI + Tool Execution |
| **OpenAI ChatGPT / Codex** | `ChatGPT_Codex_Home/`, `ChatGPT_Codex_CANCOM/` | Active | Strict System Prompt & Turnkey Delivery |
| **Anthropic Claude** | `CLAUDE_Home/`, `CLAUDE_CANCOM/` | Active | XML tag isolation & reasoning standards |
| **GitHub Copilot** | `Copilot/` | Active | In-IDE completion & workspace rules |
| **VS Code & Cursor** | `VS_Code/` | Active | `.cursorrules` / `.vscode` automation |
| **Perplexity AI** | `Perplexity/` | Active | Search & web ground-truth grounding |

---

## 📋 Version History & Changelog

<details>
<summary><b>Click to expand changelog</b></summary>

### v2026-11 (Latest)
* Fixed Markdown block formatting syntax across documentation.
* Standardized 100% English documentation and cross-model compatibility matrix.
* Synchronized token economy manifests and rules routing.

### v2026-10
* Initial release of the unified two-step sandboxing and model profile repository.

</details>

---

<div align="center">

<h3>= Rooted by VladiMIR + AI =</h3>

<a href="https://github.com/GinCz" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/GitHub-GinCz-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
&nbsp;&nbsp;<b>|||</b>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/gincz/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-Vladimir%20Bulantsev-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<br/><br/>

<sub>RULES &copy; 2026. Vladimir Bulantsev</sub>

</div>
