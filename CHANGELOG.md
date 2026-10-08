# KATHANA — CHANGELOG

All notable public changes to Kathana are documented in this file.

Kathana follows a release-based development model. Public release notes describe what is included in each distributed version, while internal development history remains in the private development repository.

---

# v0.1.0 — Beta

**Release:** Kathana Beta v0.1.0  
**Release period:** October 2026  
**Status:** Public Beta  
**Current public platform:** macOS Apple Silicon (arm64)

## Overview

Kathana Beta v0.1.0 establishes the first public Beta release of the Kathana desktop writing environment together with its local-first screenplay architecture and account system.

This release brings together the writing environment, local screenplay files, trial system, account authentication, Beta entitlement, documentation, support structure, and public distribution process.

---

## Writing Environment

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
- Multiple document windows

---

## Indian Language and Script Support

Kathana Beta includes support for writing using multiple Indian scripts, including Kannada.

The writing environment includes script-aware text handling designed for complex writing systems.

This includes grapheme-aware cursor movement and deletion so that combined characters and script-specific text are handled more naturally during editing.

---

## File Handling

Kathana Beta introduces the `.kathana` native screenplay project format.

The release includes:

- Save As
- Reopen
- Local screenplay storage
- Local backup and recovery workflows
- Multiple-window support
- DOCX import
- Word export
- PDF export
- Fountain export

Import and export results should be reviewed before being used for important production, submission, publication, or archival purposes.

---

## Local-First Architecture

Kathana Beta is designed as an offline-first, local-first desktop application.

The release establishes the following architectural principle:

> **Download is public. Trial is public. Account is identity. Screenplays remain local.**

Screenplay projects are designed to remain on the user's computer.

Kathana Beta does not operate as a cloud screenplay-storage or screenplay-synchronisation service.

The account system is separate from screenplay storage.

---

## Trial System

Kathana Beta includes a:

**14-day full-feature trial**

The trial is designed to allow users to evaluate the complete writing environment rather than an artificially restricted demonstration.

Trial state is maintained locally on the user's device.

The trial mechanism does not require screenplay content to be uploaded to the account backend.

After the trial period ends, eligible account sign-in is required to continue editing.

---

## Account and Authentication

The Beta introduces the Kathana account system.

Account functionality includes:

- Email-based authentication
- 6-digit verification codes
- Account identity
- Beta entitlement
- Account status
- Acquisition information
- Terms acceptance records
- Account-related support

The account system does not function as cloud screenplay storage.

An authenticated account does not provide access to a user's local screenplay files through a server.

---

## Post-Trial Access

After the applicable trial period expires, Kathana may enter an editing-restricted state.

Existing local screenplay files remain on the user's computer.

The Beta allows continued access to existing work for opening and exporting while editing requires an eligible account.

This architecture is intended to avoid making a writer's existing local work inaccessible simply because a trial period has ended.

---

## Offline Behaviour

Kathana is designed to keep the writing environment usable locally.

Online connectivity may be required for certain account operations, including:

- Authentication
- Email verification
- Account entitlement checks
- Other online account services

The absence of an Internet connection does not turn Kathana into a cloud-only writing application.

---

## Privacy Architecture

The Beta establishes a deliberate separation between:

**Account information**

and

**Screenplay content stored locally by the writer.**

Account-related services may process information necessary for authentication, Beta access, support, and service administration.

The normal writing workflow does not require screenplay content to be uploaded to the account backend.

The public Privacy Policy documents this architecture in greater detail.

---

## Help, Support and Community

The Beta establishes separate paths for:

- User documentation
- Technical support
- Account support
- Community resources

Support is provided through:

**jagnaam.kathana.app@gmail.com**

Users are encouraged not to send screenplay files or confidential creative material to support unless it is genuinely necessary.

---

## Security Architecture

The Beta desktop application uses Electron security controls including:

- Context isolation
- Disabled Node.js integration in the renderer
- Sandboxed renderer operation
- Controlled local application origin
- Restricted network access
- Controlled `.kathana` file handling

The application also separates local screenplay operations from its online account services.

No software system can guarantee complete security.

---

## Public Distribution

Kathana Beta v0.1.0 is distributed through the public Kathana repository.

The public repository contains:

- Public release packages
- Release notes
- Documentation
- Checksums
- Third-party notices
- Support information
- Product information

Proprietary development source code remains in a separate private repository.

---

## Current Platform Availability

The v0.1.0 public release currently includes:

**macOS Apple Silicon (arm64)**

Additional platform builds may be published separately once they are built and verified.

Platform availability is therefore considered part of the release record and may expand in later versions.

---

## Release Integrity

The macOS release includes a SHA-256 checksum so users can verify the integrity of the downloaded release package.

The checksum is published alongside the corresponding release files.

---

## Third-Party Software

Kathana Beta includes and uses third-party software, libraries, fonts, frameworks, and services.

Applicable notices and licence information are provided separately in:

[`THIRD-PARTY-NOTICES.md`](notices/THIRD-PARTY-NOTICES.md)

Third-party licences remain applicable independently of Kathana's proprietary software and branding.

---

## Beta Considerations

Kathana Beta v0.1.0 is an early public release.

Users should expect that:

- features may change;
- interfaces may change;
- bugs may occur;
- compatibility may vary;
- account services may evolve;
- platform availability may expand;
- file-format behaviour may evolve;
- and future releases may not preserve every Beta behaviour.

The Beta should therefore not be treated as a guarantee of future product functionality.

---

# Future Releases

Future entries will be added above this section in reverse chronological order.

Each release entry may document:

- Version
- Release status
- Platform availability
- New features
- Improvements
- Fixes
- Security changes
- Account changes
- File-format changes
- Compatibility changes
- Known release considerations
- Distribution information

Only changes included in an actual public release should be recorded as released functionality.

Internal experiments, unfinished features, private development work, and unreleased ideas do not belong in this public changelog until they become part of a public release.

---

**© 2026 JAGNAAM PICTURES. All rights reserved.**