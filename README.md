<div align="center">

# Kathana · ಕಥನ

### Where Stories Find Their Form

**ನಿಮ್ಮ ಕಥೆ, ನಿಮ್ಮದೇ · Your Story Stays Yours**

An independent, local-first screenwriting environment for English and Indian scripts, built by a filmmaker for the realities of Indian cinema.

[Website](https://jagnaampictures.github.io/kathana-website/) · [Download](https://github.com/jagnaampictures/kathana/releases/tag/v0.1.0) · [Online User Guide](https://jagnaampictures.github.io/kathana-website/Kathana_Online_User_Guide.html) · [Release Notes](releases/v0.1.0/RELEASE-NOTES.md) · [Support](docs/SUPPORT.md)

**JAGNAAM PICTURES**

</div>

---

> **Download is public. Trial is public. Account is identity. Screenplays remain local.**

---

## Why Kathana Exists

Kathana did not begin as a product. It began at a filmmaker's own writing desk.

Its creator, Manju S Padmanabh, is an independent Kannada filmmaker based in Bengaluru. While writing his own films in Kannada and English, he wanted a screenwriting environment that was affordable, private, and considerate of Indian languages.

Kathana grew from that need: a place for writers to shape ideas, develop stories, and bring them to life on their own computers.

Designed as an **offline-first, local-first desktop application**, Kathana places the writer's work at the centre of the writing experience.

---

## Kathana Beta v0.1.0

Kathana Beta v0.1.0 is the first public Beta release of the Kathana desktop writing environment.

It provides a practical screenplay-writing environment while keeping the writer's creative work on the writer's own computer.

The Beta combines a writing environment with a separate account and entitlement system. The account system exists for identity, authentication, Beta access, and related service administration—not for storing your screenplay.

**Kathana Beta is free during the Beta period.** Pricing and licensing for the full release will be announced separately.

The Beta is an early public release. Features, interfaces, compatibility, and service behaviour may evolve as Kathana develops.

---

## Core Principles

### Your screenplay stays local

Kathana is designed to keep your screenplay projects on your computer.

Kathana Beta does not provide cloud screenplay storage or automatic screenplay synchronisation.

Your `.kathana` project files are stored locally and are intended to remain under your control on your own device.

The native project format uses readable UTF-8 JSON, allowing the underlying file structure to be inspected with a text editor. For normal screenplay editing, use Kathana.

### Your account is separate from your writing

An account may be used for:

- Email authentication
- Beta entitlement
- Account status
- Acquisition information
- Terms acceptance
- Account-related support

Your account is **not a cloud container for your screenplay**.

### Your trial is local

Kathana Beta provides a **14-day full-feature trial**.

The trial state is maintained locally on the computer. The normal writing workflow does not require screenplay content to be uploaded to the account backend.

After the trial ends, eligible account sign-in is required to continue editing under the application's access rules.

Existing local screenplay files remain on your computer. The operations available after the trial are subject to the application's access rules.

### Kathana respects the writer's work

- **Local-first writing.** Kathana Beta does not provide cloud screenplay storage or automatic screenplay synchronisation.
- **Your words remain yours.** Kathana is a writing environment, not an AI text-generation service. It is designed to let you write and shape your own screenplay.
- **Readable project structure.** The `.kathana` format uses readable JSON rather than an intentionally opaque screenplay container.
- **Your backups matter.** Maintain independent backups of important projects. Local storage does not protect against device failure, accidental deletion, or damage to the only copy of a file.

---

## The Writing Environment

Kathana is built for writers who want a focused screenplay environment without making cloud storage a requirement.

| Area | Features |
|---|---|
| **Screenplay craft** | Screenplay writing and formatting · Scene-based writing · Scene controls · Omitted scenes · Dual dialogue |
| **Structure and planning** | Virtual corkboard and index cards with scene synopses · Integrated character manager |
| **Presentation** | Title pages · Headers and footers · Script preview · Pagination rules |
| **Workspace** | Search · Settings · Light and dark themes · Application menus · Multiple windows |
| **Protection of your work** | Save As and reopen workflows · Local backup and recovery features |

Features involving verified saves, automated backup rotation, or recovery should be understood according to the implementation in the published Beta. Keep independent copies of important work regardless of the application's recovery features.

### Writing in Kannada and Indian scripts

Kathana is designed for writing in English and Indian scripts, with script-aware text handling intended to preserve correct cursor movement and deletion for complex writing systems.

The Beta's language-related capabilities include:

- **Typography for Indian scripts.** A minimum line-height of 1.7 is used to provide additional vertical clearance for subscript consonants and vowel signs.
- **Phonetic Kannada typing.** The `Alt+K` workflow supports typing Kannada using Roman letters and transliterating the input into Unicode text.
- **Vector PDF output.** The PDF workflow uses text shaping and font-subsetting technologies, including HarfBuzz and TrueType font subsetting, to support searchable and selectable text where the source text, fonts, and shaping pipeline permit it.

Support can vary by script, font, input method, and export workflow. Review important documents after saving or exporting them.

---

## File Formats

Kathana Beta uses its native screenplay project format:

**`.kathana`**

The native format is designed for use with Kathana as the screenplay editor. Its readable JSON structure also makes the underlying data inspectable in a text editor.

The Beta supports selected import and export workflows.

| Operation | Formats |
|---|---|
| **Import** | DOCX · Final Draft (`.fdx`) · Fountain · Scrite (`.scrite`) |
| **Export** | Word-compatible documents · PDF · Final Draft (`.fdx`) · Fountain |

Import and export compatibility is not a guarantee of perfect formatting or feature-for-feature conversion between applications.

Formatting, pagination, character shaping, scene structure, line breaks, and other details may vary between source applications and export formats.

Before an important submission, production, publication, or other professional use:

1. Keep a copy of the original project.
2. Review the imported screenplay in Kathana.
3. Open exported files in their intended applications.
4. Check pagination, formatting, special characters, and Indian-script text.

---

## Download

Kathana Beta v0.1.0 is distributed through the official GitHub Release.

**Downloading the public release does not require an account or email address.**

Choose the installer for your operating system.

| Platform | Architecture | Installer |
|---|---|---|
| macOS | Apple Silicon (`arm64`) | [Download Kathana Beta v0.1.0 for macOS](https://github.com/jagnaampictures/kathana/releases/download/v0.1.0/Kathana-Beta-v0.1.0-mac-arm64.dmg) |
| Windows | 64-bit (`x64`) | [Download Kathana Beta v0.1.0 for Windows](https://github.com/jagnaampictures/kathana/releases/download/v0.1.0/Kathana-Beta-v0.1.0-win-x64.exe) |
| Linux | 64-bit (`x86_64`) | [Download Kathana Beta v0.1.0 for Linux](https://github.com/jagnaampictures/kathana/releases/download/v0.1.0/Kathana-Beta-v0.1.0-linux-x86_64.AppImage) |

### First launch

#### macOS — Apple Silicon

This build targets Apple Silicon Macs. **Intel Macs are not supported by this build.**

The macOS build is not signed with a Developer ID Application certificate and is not notarized by Apple. macOS may display a security warning when opening it for the first time.

Before opening the application:

1. Download the DMG from the official Kathana GitHub Release.
2. Verify the downloaded file against the published SHA-256 checksum.
3. Open the DMG and drag Kathana to Applications.
4. If macOS displays a security warning, verify the publisher and download source before deciding whether to proceed.

Do not disable macOS security protections globally to run an application.

#### Windows — x64

This installer targets 64-bit Windows systems.

Download the installer from the official release. If Windows displays a security or reputation warning, verify the download source and checksum before deciding whether to proceed.

#### Linux — x86_64

This AppImage targets 64-bit Linux systems. Compatibility may vary by distribution, desktop environment, system configuration, and available system libraries.

Depending on your distribution, you may need to make the AppImage executable:

```bash
chmod +x Kathana-Beta-v0.1.0-linux-x86_64.AppImage
```

You can then launch it according to your desktop environment's AppImage support or from a terminal.

Some systems may require FUSE compatibility libraries. Requirements vary by distribution.

### Release files and integrity

- [Beta v0.1.0 Release Notes](releases/v0.1.0/RELEASE-NOTES.md)
- [SHA-256 checksums for all platforms](releases/v0.1.0/SHA256.txt)

SHA-256 checksums allow you to compare a downloaded installer against its published value.

To verify a download, run the appropriate command in a terminal or shell from the directory containing the installer.

**macOS**

```bash
shasum -a 256 Kathana-Beta-v0.1.0-mac-arm64.dmg
```

**Windows PowerShell**

```powershell
Get-FileHash .\Kathana-Beta-v0.1.0-win-x64.exe -Algorithm SHA256
```

**Linux**

```bash
sha256sum Kathana-Beta-v0.1.0-linux-x86_64.AppImage
```

Compare the resulting 64-character hexadecimal hash with the corresponding value in `SHA256.txt`.

A matching checksum confirms that the downloaded file matches the published checksum value. It does not independently establish that the software is safe or free from defects.

Please download Kathana only from an official Kathana distribution channel.

---

## Account and Authentication

Kathana Beta uses email-based authentication.

The authentication flow uses a **six-digit verification code** sent to the email address associated with the account.

The account system may determine:

- Account identity
- Beta eligibility
- Entitlement status
- Terms acceptance
- Other limited information required to operate the Beta

An account is not required simply to download the public release or begin the trial.

Account-related operations may require an internet connection. The account system is separate from the local screenplay files stored on your computer.

---

## What Kathana Does Not Provide in the Beta

Kathana Beta does not provide:

- Cloud screenplay storage
- Automatic screenplay synchronisation
- A server-side screenplay backup
- An account-based screenplay library

If you use Kathana on more than one computer, your local screenplay files do not automatically appear on another computer through your Kathana account.

You remain responsible for maintaining independent backups of important work.

Signing in on another computer does not, by itself, transfer or restore your screenplay projects.

---

## Privacy

Kathana's architecture intentionally separates account information from screenplay content.

The normal writing workflow does not require your screenplay to be uploaded to Kathana's account backend.

Account authentication, entitlement, support communications, and other connected services may involve information separate from your screenplay files.

For details about account information, authentication, support communications, third-party services, retention, and privacy rights, see:

- [Privacy Policy](docs/PRIVACY.md)
- [Terms and Conditions](docs/TERMS.md)

Please read these documents to understand the data-handling practices and terms applicable to the Beta.

---

## Help, Support and Community

Kathana provides separate paths for support, documentation, and community resources.

### Support and Documentation

For technical issues, account problems, trial issues, file-related questions, and other support matters, see:

- [Support Guide](docs/SUPPORT.md)
- [User Guide](docs/USER-GUIDE.md)
- [Online User Guide](https://jagnaampictures.github.io/kathana-website/Kathana_Online_User_Guide.html)
- [Report an Issue](https://github.com/jagnaampictures/kathana/issues)

**Official support:** [jagnaam.kathana.app@gmail.com](mailto:jagnaam.kathana.app@gmail.com)

When reporting a problem, include useful details such as your operating system, Kathana version, the steps that led to the issue, and any relevant error message.

Please do not include confidential screenplay pages, unpublished dialogue, or other sensitive creative material in support requests. If a minimal example is necessary to reproduce a problem, remove private story material first.

### Community

Kathana may provide access to community resources where writers can connect, discuss the application, share knowledge, and participate in the wider Kathana community.

Community participation is separate from Kathana's local screenplay-storage architecture.

Do not share confidential screenplay material or personal information publicly unless you have decided that doing so is appropriate.

---

## Documentation

| Document | Purpose |
|---|---|
| [User Guide](docs/USER-GUIDE.md) | Using the writing environment |
| [Privacy Policy](docs/PRIVACY.md) | Account data and privacy practices |
| [Terms and Conditions](docs/TERMS.md) | Terms applicable to Kathana |
| [Support Guide](docs/SUPPORT.md) | Getting help |
| [Third-Party Notices](notices/THIRD-PARTY-NOTICES.md) | Notices and licences for included components |
| [Beta v0.1.0 Release Notes](releases/v0.1.0/RELEASE-NOTES.md) | Details of this release |
| [Changelog](CHANGELOG.md) | Version history |
| [SHA-256 checksums](releases/v0.1.0/SHA256.txt) | Published installer hashes |

Additional public resources:

- [Official Kathana Website](https://jagnaampictures.github.io/kathana-website/)
- [Online User Guide](https://jagnaampictures.github.io/kathana-website/Kathana_Online_User_Guide.html)
- [GitHub Releases](https://github.com/jagnaampictures/kathana/releases)
- [Report an Issue](https://github.com/jagnaampictures/kathana/issues)

---

## Third-Party Software

Kathana includes and/or uses third-party software, libraries, fonts, frameworks, and services.

Third-party components remain subject to their respective licences. See the [Third-Party Notices](notices/THIRD-PARTY-NOTICES.md) for applicable notices.

The presence of a third-party component does not imply that its original authors endorse Kathana.

---

## Beta Status

Kathana Beta v0.1.0 is an early public release.

Features, interfaces, compatibility, account services, and file-format behaviour may change in future releases.

Some workflows and platform combinations may not yet have been exhaustively tested. Report reproducible problems through the official support channel or the repository's issue tracker.

Maintain independent backups of important screenplay projects. Review imported and exported documents before relying on them for professional use.

The Beta is provided as an evolving application, and users should exercise appropriate care when working with important creative material.

---

<div align="center">

### Where Stories Find Their Form

**Kathana · ಕಥನ**

Published by **JAGNAAM PICTURES**  
Bengaluru, Karnataka, India

[Website](https://jagnaampictures.github.io/kathana-website/) · [Download](https://github.com/jagnaampictures/kathana/releases/tag/v0.1.0) · [Online User Guide](https://jagnaampictures.github.io/kathana-website/Kathana_Online_User_Guide.html) · [Support](docs/SUPPORT.md)

**© 2026 JAGNAAM PICTURES. All rights reserved.**

</div>
