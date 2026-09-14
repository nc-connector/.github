<p align="center">
  <img
    src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/header-solid-blue.png"
    alt="NC Connector header"
    width="1280"
  />
</p>

<p align="center">
  <b>Open-source Nextcloud integrations for Thunderbird and Outlook Classic.</b><br/>
  Share files, create Talk meetings, and handle attachments without leaving your mail or calendar.
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

## Share files and plan meetings

- Combine files and folders from your computer and **My Nextcloud** in one share. Existing Nextcloud files are copied into the share; the originals stay unchanged.
- Send links instead of large attachments, with passwords, expiration dates, and access permissions.
- Use attachment rules to share large attachments or route all attachments through NC Connector.
- Create and update Talk meetings from calendar events, with password protection, a lobby, and moderation options.
- View Nextcloud availability in Outlook's Scheduling Assistant.

<p align="center">
  <a href="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/sharing-queue-outlook.jpg">
    <img src="https://raw.githubusercontent.com/nc-connector/.github/refs/heads/main/profile/sharing-queue-outlook.jpg" alt="Outlook sharing queue with local files, My Nextcloud, an expandable folder tree, and the target folder" width="680">
  </a>
  <br/>
  <em>Sharing queue in Outlook Classic. Click the image to enlarge.</em>
</p>

## Projects

| Project | What it does | Links |
|---|---|---|
| **NC Connector for Thunderbird** | Nextcloud sharing, Talk meetings, and attachment rules in Thunderbird | [Repo](https://github.com/nc-connector/NC_Connector_for_Thunderbird) · [Install from ATN](https://addons.thunderbird.net/thunderbird/addon/nc4tb/) · [Releases](https://github.com/nc-connector/NC_Connector_for_Thunderbird/releases/latest) |
| **NC Connector for Outlook Classic** | Nextcloud sharing, Talk meetings, attachment rules, and calendar availability in Outlook Classic | [Repo](https://github.com/nc-connector/NC_Connector_for_Outlook) · [Releases](https://github.com/nc-connector/NC_Connector_for_Outlook/releases/latest) |
| **NC Connector Backend** | Optional Nextcloud app for Pro features and central management, with one free user seat | [Repo](https://github.com/nc-connector/Server_Backend) · [Install from App Store](https://apps.nextcloud.com/apps/ncc_backend_4mc) |
| **VFS Provider for Google Drive** | Separate add-on that connects Google Drive to compatible Thunderbird add-ons | [Repo and setup](https://github.com/nc-connector/vfs-provider-googledrive) |

## One user free, Pro for your team

Sharing, **My Nextcloud**, Talk, and attachment rules work without NC Connector Backend.

The optional backend includes **one free Community seat**. Each seat is assigned to exactly one Nextcloud user and unlocks **all Pro features for that user**:

- Central settings and policies, with admin locks and delegated management
- Centrally managed email signatures
- Custom templates and branding for shares and Talk invitations
- Separate password delivery by email or one-time Nextcloud Secrets links; the latter also require the Secrets app
- Additional sources such as Google Drive, OneDrive, WebDAV, and compatible storage **in Thunderbird only**, using the respective provider add-ons

Pro features are available only to users with an assigned seat. The free Community seat is sufficient; paid Pro plans provide the same features for teams, starting at five seats.

[Install the free backend](https://apps.nextcloud.com/apps/ncc_backend_4mc) · [Plans and licensing](https://nc-connector.de/preise-lizenzierung/)

## Open source and your data

File sharing and Talk use your own Nextcloud. Connected storage providers access the services you choose; file contents are not relayed through an NC Connector-hosted service.

Update checks contact NC Connector for release information and anonymous usage counts. Backend license checks are separate from file transfers. Source code, release history, and third-party dependency notices are available in the project repositories.

[Trust and transparency](https://nc-connector.de/vertrauen-transparenz/)

## Documentation and support

- Setup and administration: [Thunderbird](https://github.com/nc-connector/NC_Connector_for_Thunderbird/blob/main/docs/ADMIN.md) · [Outlook Classic](https://github.com/nc-connector/NC_Connector_for_Outlook/blob/main/docs/ADMIN.md)
- Planned work: [Public roadmap](https://github.com/orgs/nc-connector/projects/1)
- Questions and rollout help: [Homepage](https://nc-connector.de/) · [Contact](https://nc-connector.de/kontakt/)

For bugs or feature requests, open an issue in the relevant project repository with the affected versions and steps to reproduce. Remove credentials and personal information before attaching logs.

Feedback, GitHub stars, and [Thunderbird add-on reviews](https://addons.thunderbird.net/thunderbird/addon/nc4tb/) help others find NC Connector.
