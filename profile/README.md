<p align="center">
  <img
    src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/header-solid-blue.png"
    alt="nc-connector header"
    width="1280"
  />
</p>

<p align="center">
  <b>Community add-ons and an optional Nextcloud backend that bring Nextcloud workflows directly into mail & calendar clients.</b><br/>
  Talk meetings, secure sharing links (Filelink), central seats and policies, custom templates, and less copy-paste — with a focus on security defaults and admin-friendly diagnostics.
</p>

<p align="center">
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird">
    <img alt="Thunderbird Repo" src="https://img.shields.io/badge/Repo-NC__Connector__for__Thunderbird-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook">
    <img alt="Outlook Repo" src="https://img.shields.io/badge/Repo-NC__Connector__for__Outlook-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/Server_Backend">
    <img alt="Backend Repo" src="https://img.shields.io/badge/Repo-Server__Backend-2e6ee6?logo=github&logoColor=white">
  </a>
</p>

---

## ❤️ Support this project
If you find these connectors useful and want to support ongoing development, you can donate here:  
👉 [Paypal](https://www.paypal.com/donate/?hosted_button_id=FTZWNRNKVKUN6)

---

## 🚀 Projects

### 1) NC Connector for Thunderbird

<p align="left">
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases">
    <img alt="Releases" src="https://img.shields.io/github/v/release/nc-connector/NC_Connector_for_Thunderbird?display_name=tag&logo=github">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/License-AGPL--3.0-informational">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird/stargazers">
    <img alt="Stars" src="https://img.shields.io/github/stars/nc-connector/NC_Connector_for_Thunderbird?style=flat">
  </a>
</p>

**Repo:** https://github.com/nc-connector/NC_Connector_for_Thunderbird  
**What it solves:** Create Talk meetings from calendar events and generate secure Nextcloud shares right from the compose window — without browser detours.

**Highlights**
- ✅ **Talk wizard in calendar events:** create rooms, lobby until start time, passwords, moderator delegation
- ✅ **Sharing/Filelink wizard in emails:** upload queue, password generator, expiration date, optional note, ready-to-send HTML block
- ✅ **ESR-first:** optimized & tested for Thunderbird ESR
- ✅ **Troubleshooting-friendly:** structured debug logs

**Get it**
- Add-on Store: https://addons.thunderbird.net/thunderbird/addon/nc4tb/
- Releases/XPI: https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases/latest

---

### 2) NC Connector for Outlook (Classic)

<p align="left">
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook/releases">
    <img alt="Releases" src="https://img.shields.io/github/v/release/nc-connector/NC_Connector_for_Outlook?display_name=tag&logo=github">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/License-AGPL--3.0-informational">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook/stargazers">
    <img alt="Stars" src="https://img.shields.io/github/stars/nc-connector/NC_Connector_for_Outlook?style=flat">
  </a>
</p>

**Repo:** https://github.com/nc-connector/NC_Connector_for_Outlook  
**What it solves:** Create Talk meetings from calendar events and generate secure Nextcloud shares right from the compose window with local Free/Busy gateway — without browser detours.

**Highlights**
- ✅ **Talk wizard in calendar events:** create rooms, lobby until start time, passwords, moderator delegation
- ✅ **Sharing/Filelink wizard in emails:** upload queue, password generator, expiration date, optional note, ready-to-send HTML block
- ✅ **Troubleshooting-friendly:** structured debug logs
- ✅ **IFB (Free/Busy gateway):** local listener for availability lookups

**Get it**
- Releases/MSI: https://github.com/nc-connector/NC_Connector_for_Outlook/releases/latest

---

### 3) NC Connector Server Backend

<p align="left">
  <a href="https://github.com/nc-connector/Server_Backend">
    <img alt="Repo" src="https://img.shields.io/badge/Repo-Server__Backend-2e6ee6?logo=github&logoColor=white">
  </a>
</p>

**Repo:** https://github.com/nc-connector/Server_Backend  
**What it solves:** Add central backend capabilities for NC Connector — including seat assignment, policy delivery to mail clients, backend-driven capability control, and template management for Share and Talk.

**Highlights**
- ✅ **Central seat assignment:** one seat maps to one Nextcloud user and can be reassigned at any time
- ✅ **Central policy control:** manage mail client defaults and backend-driven capabilities
- ✅ **Separate password delivery workflow:** backend-controlled delivery flow for supported clients
- ✅ **User-specific overrides:** define per-user exceptions for seat users
- ✅ **Custom Share and Talk templates:** centrally managed text/design templates
- ✅ **Visual template editor with preview:** backend-driven template editing workflow

**Status**
- 🛠️ **Work in progress:** planned as a Nextcloud backend app for Community and Pro backend features

---

## 🎯 Vision
We build connector tools that accelerate real-world workflows:
- **Create a meeting → automatically add a Talk room**
- **Large attachments → secure share links instead of mail bloat**
- **Security defaults:** passwords, expirations, lobby/moderation
- **Central admin control:** seats, policies, templates, debug logs, reproducible diagnostics
- **One ecosystem:** connectors that can work directly in the client, with optional central backend control

---

## 🧩 Supported platforms (currently)
- **Thunderbird (ESR)**
- **Outlook Classic (Windows)**
- **Nextcloud backend app** (in progress)

---

## 🛠️ Support & feedback
- Bugs/features: please open an **issue in the relevant repository**.
- When reporting problems: enable **debug logging** (project-specific) and include the relevant log snippets.
- Backend-related questions and feature requests: please use the **Server_Backend** repository.

---

## 🤝 Contributing
PRs welcome:
- UI/wording/translations/docs
- Repro cases & testing feedback (especially ESR / Outlook Classic environments)
- Security/policy suggestions (defaults, compliance flows)
- Backend ideas for seat handling, policy delivery, and template workflows

Not sure where to start? Open an issue with your use-case.

---

## ⚠️ Disclaimer
This is a **community project** and **not an official product of Nextcloud GmbH**.  
“Thunderbird” and “Outlook” are trademarks of their respective owners.

---

<p align="center">
  <sub>Built with ❤️ for clean workflows: Calendar ↔ Talk ↔ Filesharing ↔ Email ↔ Backend policies</sub>
</p>
