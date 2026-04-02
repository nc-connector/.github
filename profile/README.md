<p align="center">
  <img
    src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/header-solid-blue.png"
    alt="nc-connector header"
    width="1280"
  />
</p>

<p align="center">
  <b>Nextcloud workflows directly inside mail and calendar clients.</b><br/>
  Sharing, Talk meetings, attachment automation, and optional central backend control.
</p>

<p align="center">
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird">
    <img alt="Thunderbird Repo" src="https://img.shields.io/badge/Thunderbird-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook">
    <img alt="Outlook Repo" src="https://img.shields.io/badge/Outlook_Classic-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/Server_Backend">
    <img alt="Backend Repo" src="https://img.shields.io/badge/Server_Backend-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
</p>

---

## 🚀 Projects

### NC Connector Mail Clients

Bring Nextcloud sharing and Talk directly into Thunderbird and Outlook Classic.

**What it solves**
- Create secure Nextcloud shares directly while composing
- Create Nextcloud Talk meetings from calendar events
- Reduce browser detours and copy-paste workflows
- Keep sharing and meeting workflows inside the mail client

**Core capabilities**
- ✅ Guided sharing workflow with files, expiration date, note, and formatted share block
- ✅ Attachment automation directly in the compose flow
- ✅ Talk room creation from calendar events
- ✅ Security defaults such as passwords, expirations, lobby, and moderation
- ✅ Structured debug logs for troubleshooting

| Client | Status | Notes | Get it |
|---|---|---|---|
| **Thunderbird** | Available | ESR-first, add-on store listing | [Repo](https://github.com/nc-connector/NC_Connector_for_Thunderbird) · [ATN](https://addons.thunderbird.net/thunderbird/addon/nc4tb/) · [Releases](https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases/latest) |
| **Outlook Classic** | Available | Includes local IFB / Free-Busy gateway | [Repo](https://github.com/nc-connector/NC_Connector_for_Outlook) · [Releases](https://github.com/nc-connector/NC_Connector_for_Outlook/releases/latest) |

---

## Backend capabilities

> [!NOTE]
> With the Nextcloud backend, seats, policies, and backend-driven workflows can be managed centrally.  
> One seat maps to one Nextcloud user and can be reassigned at any time.

| Capability | Without backend | With backend |
|---|:---:|:---:|
| **Start directly in mail client** | ✅ | ✅ |
| **Seat assignment and central policy control** | ❌ | ✅ |
| **Separate password delivery workflow** | ❌ | ✅ |
| **User-specific policy overrides** | ❌ | ✅ |
| **Custom Share and Talk templates** | ❌ | ✅ |
| **Visual template editor with preview** | ❌ | ✅ |

### NC Connector Server Backend

Optional Nextcloud backend for central administration of NC Connector.

**What it solves**
- Central seat assignment
- Central policy delivery to mail clients
- Backend-controlled capability management
- Central template management for Share and Talk

**Status**
- Released !
- [Nextcloud App Store](https://apps.nextcloud.com/apps/ncc_backend_4mc)
  https://apps.nextcloud.com/apps/ncc_backend_4mc

**Repo**
- [Server_Backend](https://github.com/nc-connector/Server_Backend)

---

## 🎯 Vision

NC Connector is built around practical workflows:

- **Create a meeting → add a Talk room**
- **Handle large attachments → create secure share links**
- **Apply security defaults → passwords, expirations, lobby, moderation**
- **Manage environments centrally → seats, policies, templates, diagnostics**

---

## 🧩 Supported platforms

- Thunderbird (ESR)
- Outlook Classic (Windows)
- Nextcloud backend app (in progress)

---

## 🛠️ Support & feedback

- Bugs and feature requests: open an issue in the relevant repository
- Please include debug logs where available
- Backend-related topics belong in the `Server_Backend` repository

---

## 🤝 Contributing

Contributions are welcome:
- UI / wording / translations / docs
- testing feedback and repro cases
- security and policy ideas
- backend concepts for seats, policies, and templates

If you are unsure where to start, open an issue with your use case.

---

## ❤️ Support this project

If you find NC Connector useful and want to support ongoing development:

👉 [Paypal](https://www.paypal.com/donate/?hosted_button_id=FTZWNRNKVKUN6)

---

## ⚠️ Disclaimer

This is a **community project** and **not an official product of Nextcloud GmbH**.  
“Thunderbird” and “Outlook” are trademarks of their respective owners.

---

<p align="center">
  <sub>Calendar ↔ Talk ↔ Filesharing ↔ Email ↔ Backend policies</sub>
</p>
