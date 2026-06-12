<p align="center">
  <img
    src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/header-solid-blue.png"
    alt="NC Connector header"
    width="1280"
  />
</p>

<p align="center">
  <b>Open-source Nextcloud integrations for Thunderbird and Outlook Classic.</b><br/>
  File sharing, Talk rooms, central signatures, attachment rules, and policy control on your own Nextcloud infrastructure.
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

## Position

NC Connector keeps everyday team workflows where people already work: in mail and calendar clients.

It connects Thunderbird and Outlook Classic to Nextcloud without routing file shares, meeting links, signatures, or policy decisions through a third-party SaaS. The clients stay close to the user. The backend, when used, stays on your Nextcloud.

## Projects

| Project | What it does | Links |
|---|---|---|
| **NC Connector for Thunderbird** | Thunderbird-native sharing, Talk meetings, attachment rules, and backend-managed signatures | [Repo](https://github.com/nc-connector/NC_Connector_for_Thunderbird) · [ATN](https://addons.thunderbird.net/thunderbird/addon/nc4tb/) · [Releases](https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases/latest) |
| **NC Connector for Outlook Classic** | COM add-in for Nextcloud shares, Talk workflows, IFB/Free-Busy, signatures, and update checks | [Repo](https://github.com/nc-connector/NC_Connector_for_Outlook) · [Releases](https://github.com/nc-connector/NC_Connector_for_Outlook/releases/latest) |
| **NC Connector Server Backend** | Optional Nextcloud app for seats, policies, templates, signatures, and team-wide defaults | [Repo](https://github.com/nc-connector/Server_Backend) · [App Store](https://apps.nextcloud.com/apps/ncc_backend_4mc) |

## What NC Connector Covers

- Nextcloud file shares directly from compose windows, replies, and forwards
- Large file uploads with chunked WebDAV where supported
- Passwords, expiration dates, permissions, and separate password delivery
- Nextcloud Secret links for password delivery when the backend and Secrets app are available
- Talk rooms from calendar events, including lobby and moderation options
- Central email signatures with sender matching and policy controls
- Attachment automation rules for large or all attachments
- Backend policies for teams that need central defaults and locked settings
- Debug logs for support without requiring users to inspect source code

## Backend Or No Backend

NC Connector can be used directly with a Nextcloud account. That is enough for local sharing and Talk workflows.

The backend is useful when an organization needs central rules:

- which users have seats
- which sharing defaults apply
- whether options are editable by users
- which templates are used for share blocks, password mails, Talk invitations, and signatures
- whether password delivery should use plaintext mail or Nextcloud Secret links

## Trust Model

- Source code and release history are public on GitHub
- Client-side data stays between the mail client and your Nextcloud
- No client telemetry is required for the add-ins to work
- Backend operation is self-hosted inside Nextcloud
- Admin-controlled settings are visible to users instead of being silently hidden
- Third-party libraries are vendored and documented in each repository

## Website

- [Homepage](https://nc-connector.de/)
- [Pricing and licensing](https://nc-connector.de/preise-lizenzierung/)
- [Trust and transparency](https://nc-connector.de/vertrauen-transparenz/)
- [Contact](https://nc-connector.de/kontakt/)

## Support

Please open issues in the relevant repository:

- Thunderbird topics: [NC_Connector_for_Thunderbird](https://github.com/nc-connector/NC_Connector_for_Thunderbird/issues)
- Outlook topics: [NC_Connector_for_Outlook](https://github.com/nc-connector/NC_Connector_for_Outlook/issues)
- Backend topics: [Server_Backend](https://github.com/nc-connector/Server_Backend/issues)

Useful issue details:

- product and version
- Thunderbird or Outlook version
- Nextcloud version and enabled apps
- backend version, if used
- relevant debug logs with secrets removed
- short reproduction steps

## Support The Project

If NC Connector helps your team, stars and feedback help others find it:

- ⭐ [Star NC Connector for Thunderbird](https://github.com/nc-connector/NC_Connector_for_Thunderbird)
- ⭐ [Star NC Connector for Outlook Classic](https://github.com/nc-connector/NC_Connector_for_Outlook)
- ⭐ [Star NC Connector Server Backend](https://github.com/nc-connector/Server_Backend)
- [Rate the Thunderbird add-on on ATN](https://addons.thunderbird.net/de/thunderbird/addon/nc4tb/)

For teams using the backend in production, see [pricing and licensing](https://nc-connector.de/preise-lizenzierung/).
