<p align="center">
  <img
    src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/header-solid-blue.png"
    alt="NC Connector header"
    width="1280"
  />
</p>

<p align="center">
  <b>Nextcloud workflows directly inside mail and calendar clients.</b><br/>
  Share files, create Talk meetings, automate attachment handling, and optionally manage policies centrally with the backend.
</p>

<p align="center">
  <a href="https://github.com/nc-connector/NC_Connector_for_Thunderbird">
    <img alt="Thunderbird" src="https://img.shields.io/badge/Thunderbird-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/NC_Connector_for_Outlook">
    <img alt="Outlook Classic" src="https://img.shields.io/badge/Outlook_Classic-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://github.com/nc-connector/Server_Backend">
    <img alt="Server Backend" src="https://img.shields.io/badge/Server_Backend-Repo-2e6ee6?logo=github&logoColor=white">
  </a>
  <a href="https://apps.nextcloud.com/apps/ncc_backend_4mc">
    <img alt="Nextcloud App Store" src="https://img.shields.io/badge/Nextcloud-App_Store-0082c9?logo=nextcloud&logoColor=white">
  </a>
</p>

---

## Projects

| Project | Purpose | Status | Links |
|---|---|---|---|
| **NC Connector for Thunderbird** | Add-on for sharing and Talk workflows in Thunderbird ESR | Active | [Repo](https://github.com/nc-connector/NC_Connector_for_Thunderbird) · [ATN](https://addons.thunderbird.net/thunderbird/addon/nc4tb/) · [Releases](https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases/latest) |
| **NC Connector for Outlook Classic** | COM Add-in for sharing, Talk workflows, and IFB/Free-Busy integration | Active | [Repo](https://github.com/nc-connector/NC_Connector_for_Outlook) · [Releases](https://github.com/nc-connector/NC_Connector_for_Outlook/releases/latest) |
| **NC Connector Server Backend** | Optional Nextcloud backend for central policy and seat management | Active | [Repo](https://github.com/nc-connector/Server_Backend) · [App Store](https://apps.nextcloud.com/apps/ncc_backend_4mc) |

---

## Operating modes

| Mode | Account on nc-connector.de | Seats | Billing | Typical use |
|---|---|---|---|---|
| **Add-ons without backend** | No | Not required | None | Direct start in mail client |
| **Backend Community** | No | 1 free seat | None | Small setups with central backend |
| **Backend Pro** | Yes | 5+ seats | Subscription | Productive team operation |

> One seat maps to one Nextcloud user and can be reassigned at any time.

---

## Core capabilities

- Guided file sharing workflow directly in the compose window
- Attachment automation rules and thresholds
- Talk room creation from calendar events
- Security defaults such as passwords, expirations, lobby, and moderation
- Structured debug logs for support and troubleshooting
- Optional backend control for central policies, seat assignment, and templates

---

## Requirements

- Thunderbird ESR (Thunderbird add-on)
- Outlook Classic on Windows (COM Add-in)
- Nextcloud (for backend mode)
- NC Connector add-on version **>= 3.0.0** for backend policy control

---

## Support

- Please open issues in the relevant repository:
  - Thunderbird topics: `NC_Connector_for_Thunderbird`
  - Outlook topics: `NC_Connector_for_Outlook`
  - Backend topics: `Server_Backend`
- Include logs and reproduction steps where possible.

---

## Contributing

Contributions are welcome:
- Code, testing, translations, and documentation
- UX/text improvements
- Policy and backend workflow ideas

If unsure where to start, open an issue with your use case.

---

## Support this project

If NC Connector helps your team and you want to support development:

👉 [PayPal](https://www.paypal.com/donate/?hosted_button_id=FTZWNRNKVKUN6)

---

## Disclaimer

This is a **community project** and **not an official product of Nextcloud GmbH**.  
“Thunderbird” and “Outlook” are trademarks of their respective owners.
