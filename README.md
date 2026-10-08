# Kathana

### Where Stories find their form.

**JAGNAAM PICTURES**

Kathana is a creative writing application built to help writers shape ideas, develop stories, and bring them to life.

> **Download is public. Trial is public. Account is identity. Screenplays remain local.**

---

## Kathana Beta v0.1.0

Kathana Beta v0.1.0 is an early public release focused on providing a serious, practical writing environment while keeping the writer's creative work on the writer's own computer.

Kathana is designed as an **offline-first, local-first desktop application**.

The Beta combines a full writing environment with a separate account and entitlement system. The account system exists for identity, authentication, Beta access, and related service administration — not for storing your screenplay.

---

## Core Principles

### Your screenplay stays local

Kathana is designed so that your screenplay projects remain on your computer.

Kathana Beta does not operate as a cloud screenplay-storage or screenplay-synchronisation service.

Your `.kathana` files are stored locally and are intended to remain under your control on your own device.

### Your account is separate from your writing

An account may be used for:

- Email authentication
- Beta entitlement
- Account status
- Acquisition information
- Terms acceptance
- Account-related support

Your account is **not** a cloud container for your screenplay.

### Your trial is local

Kathana Beta provides a **14-day full-feature trial**.

The trial state is maintained locally on the computer rather than requiring screenplay content to be uploaded to a server.

After the trial ends, eligible account sign-in is required to continue editing.

Existing local screenplay files can still be opened and exported.

---

## Writing Environment

Kathana is built for writers who want a focused screenplay environment without making cloud storage a requirement.

The Beta includes:

- Screenplay writing and formatting
- Scene-based writing
- Scene controls
- Omitted scenes
- Dual dialogue
- Title pages
- Headers and footers
- Script preview
- Search
- Settings
- Light and dark themes
- Application menus
- Save As and reopen workflows
- Multiple windows
- Local backup and recovery features

Kathana also supports writing in **Kannada and other Indian scripts**, with script-aware text handling designed to preserve correct cursor movement and deletion for complex writing systems.

---

## File Formats

Kathana Beta works with its native:

**`.kathana`**

screenplay project format.

The Beta also provides support for selected import and export workflows, including:

- DOCX import
- Word export
- PDF export
- Fountain export

Import and export results should always be reviewed before using the resulting document for an important submission, production, publication, or other final purpose.

---

## Desktop Application

Kathana Beta v0.1.0 is distributed as a desktop application.

The current public release includes:

**macOS — Apple Silicon (arm64)**

Additional platform builds will be published when they are available and have been verified.

Kathana is intended to provide a consistent local writing experience rather than requiring a browser-based writing environment.

---

## Account and Authentication

Kathana Beta uses email-based authentication.

The Beta authentication flow uses a **6-digit verification code** sent to the email address associated with the account.

The account system may determine:

- account identity;
- Beta eligibility;
- entitlement status;
- and other limited information required to operate the Beta.

Kathana does not require an account simply to download the public release or begin the trial.

---

## What Kathana Does Not Provide in the Beta

Kathana Beta does **not** provide:

- Cloud screenplay storage
- Automatic screenplay synchronisation
- A server-side screenplay backup
- An account-based screenplay library

If you use Kathana on more than one computer, your local screenplay files do not automatically appear on another computer through your Kathana account.

You remain responsible for maintaining backups of important work.

---

## Privacy

Kathana's architecture intentionally separates account information from screenplay content.

The normal writing workflow does not require your screenplay to be uploaded to Kathana's account backend.

For information about account data, authentication, support communications, third-party services, retention, and privacy rights, see:

- [`Privacy Policy`](docs/PRIVACY.md)
- [`Terms and Conditions`](docs/TERMS.md)

---

## Help, Support and Community

Kathana provides separate paths for:

### Support & Documentation

For technical issues, account problems, trial issues, file-related questions, and other support matters.

See:

- [`Support Guide`](docs/SUPPORT.md)
- [`User Guide`](docs/USER-GUIDE.md)

Official support:

**jagnaam.kathana.app@gmail.com**

### Community

Kathana may provide access to community resources where writers can connect, discuss the application, share knowledge, and participate in the wider Kathana community.

Community participation is separate from Kathana's local screenplay storage architecture.

Do not share confidential screenplay material or personal information publicly unless you have decided that doing so is appropriate.

---

## Downloads

The current Beta release is available in the public releases section of this repository.

### Kathana Beta v0.1.0

**macOS Apple Silicon**

- [Download release](releases/v0.1.0/)
- [Release Notes](releases/v0.1.0/RELEASE-NOTES.md)
- [SHA-256 checksum](releases/v0.1.0/macOS/SHA256.txt)

The SHA-256 checksum is provided so that users can verify the integrity of the downloaded release.

---

## Documentation

- [`User Guide`](docs/USER-GUIDE.md)
- [`Privacy Policy`](docs/PRIVACY.md)
- [`Terms and Conditions`](docs/TERMS.md)
- [`Support Guide`](docs/SUPPORT.md)
- [`Third-Party Notices`](notices/THIRD-PARTY-NOTICES.md)
- [`Beta v0.1.0 Release Notes`](releases/v0.1.0/RELEASE-NOTES.md)
- [`Changelog`](CHANGELOG.md)

---

## Third-Party Software

Kathana includes and/or uses third-party software, libraries, fonts, frameworks, and services.

Those components remain subject to their respective licences and terms.

The applicable notices for the Beta are available here:

[`Third-Party Notices`](notices/THIRD-PARTY-NOTICES.md)

Kathana's proprietary software, branding, visual identity, and original product materials remain the property of their respective rights holders.

---

## Development

Kathana's proprietary source code is maintained separately in a private development repository.

This public repository is intended to provide:

- Public releases
- Release notes
- Documentation
- Checksums
- Third-party notices
- Product information
- Support information
- Public distribution material

The public repository is **not** the Kathana source-code repository.

---

## Security and Trust

Kathana is designed with separation between the local desktop application, local screenplay files, and online account services.

The Beta desktop application uses Electron security controls including:

- Context isolation
- Disabled Node.js integration in the renderer
- Sandboxed renderer operation
- A controlled local application origin
- Restricted network access
- Controlled handling of the `.kathana` file type

These measures are intended to reduce unnecessary access between application components.

No software or computer system can be guaranteed to be completely secure.

If you believe you have discovered a security issue affecting Kathana, please contact:

**jagnaam.kathana.app@gmail.com**

Please do not publicly disclose sensitive security information before giving us a reasonable opportunity to investigate it.

---

## Beta Status

Kathana Beta v0.1.0 is an early public release.

During the Beta period:

- Features may change.
- Bugs may occur.
- Compatibility may vary.
- Interfaces may change.
- Account services may change.
- Platform availability may expand.
- Future releases may not preserve every Beta behaviour.

Please review the release notes before installing or updating.

---

## Official Website

The Kathana website provides product information, documentation, and other public resources.

The website and this public repository serve different purposes:

**Website:** product presentation and public information.

**GitHub repository:** releases, documentation, notices, and public distribution material.

---

## Publisher

Kathana Beta v0.1.0 is published by:

**JAGNAAM PICTURES**

Public product identity:

**Kathana**

Future legal registration plans do not change the publisher identity stated for this Beta release.

---

## Copyright

**© 2026 JAGNAAM PICTURES. All rights reserved.**

Kathana, its branding, original visual identity, proprietary software, and original product materials are protected by applicable intellectual-property laws.

No licence to copy, modify, redistribute, or commercially exploit proprietary Kathana software or branding is granted merely by making this repository public.

Third-party components remain subject to their respective licences.

---

### Where Stories find their form.

**JAGNAAM PICTURES**