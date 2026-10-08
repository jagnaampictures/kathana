# KATHANA — BETA v0.1.0 RELEASE NOTES

**Version:** 0.1.0  
**Release:** Kathana Beta v0.1.0  
**Release period:** October 2026  
**Status:** Public Beta  
**Publisher:** JAGNAAM PICTURES

### Where Stories find their form.

---

## 1. Release Overview

Kathana Beta v0.1.0 is the first public Beta release of the Kathana desktop writing environment.

This release brings together:

- the Kathana screenplay editor;
- local `.kathana` project files;
- screenplay import and export;
- Indian-script writing support;
- local backup and recovery workflows;
- a 14-day full-feature trial;
- email-based account authentication;
- Beta entitlement;
- Help, Support, and Community pathways;
- and the public release/distribution structure.

Kathana is designed around an offline-first, local-first architecture.

> **Download is public. Trial is public. Account is identity. Screenplays remain local.**

---

# 2. Current Platform

The v0.1.0 public release currently includes:

**macOS — Apple Silicon (arm64)**

Additional platform builds may be published separately after they have been built and verified.

---

# 3. Writing Environment

Kathana Beta v0.1.0 includes a focused screenplay-writing environment with support for:

- screenplay formatting;
- scene-based writing;
- scene controls;
- omitted scenes;
- dual dialogue;
- title pages;
- headers and footers;
- screenplay preview;
- search;
- application settings;
- light and dark themes;
- application menus;
- multiple document windows.

---

# 4. Indian Language and Script Support

The Beta supports writing using multiple Indian scripts, including:

- Kannada;
- Devanagari;
- Tamil;
- Telugu;
- Malayalam;
- Bengali;
- Gujarati;
- Gurmukhi;
- Oriya;
- and other supported script configurations available in the application.

Kathana includes script-aware text handling intended for complex writing systems.

The editor also uses grapheme-aware cursor and deletion behaviour to better handle visible characters that may consist of multiple underlying Unicode elements.

---

# 5. Native Project Format

Kathana Beta uses:

**`.kathana`**

as its native screenplay project format.

Projects are designed to remain stored locally on the user's computer.

Kathana does not operate the Beta as a cloud screenplay-storage or screenplay-synchronisation service.

---

# 6. File Operations

The Beta includes:

- Save;
- Save As;
- Reopen;
- local project handling;
- multiple-window support;
- local backup functionality;
- recovery-related workflows;
- and `.kathana` project management.

Users should maintain independent backups of important work.

---

# 7. Import and Export

Kathana Beta supports:

### Import

- DOCX

### Export

- Word-compatible documents;
- PDF;
- Fountain.

Import and export are conversion processes.

Formatting, fonts, metadata, layout, or other characteristics may differ from the original document or from another application.

Users should review important exported documents before using them for production, publication, submission, or other final purposes.

---

# 8. Preview and Review

The Beta includes screenplay preview functionality.

Preview can be used to review:

- screenplay structure;
- dialogue;
- page flow;
- title pages;
- headers and footers;
- and general presentation.

Preview does not replace reviewing the final exported file.

---

# 9. Trial

Kathana Beta v0.1.0 provides:

**14 days of full-feature trial access.**

The trial is designed to allow users to experience the writing environment without intentionally restricting the core writing workflow.

Trial state is maintained locally on the user's computer.

The trial does not require screenplay content to be uploaded to Kathana's account backend.

---

# 10. Account System

The Beta introduces the Kathana account system.

Account functionality includes:

- email-based authentication;
- 6-digit verification codes;
- account identity;
- Beta entitlement;
- account status;
- acquisition information;
- Terms acceptance;
- and related account administration.

An account is used for identity and service access.

It is not a cloud screenplay library.

---

# 11. Post-Trial Behaviour

After the applicable trial period ends, Kathana may require an eligible account sign-in to continue editing.

Existing local screenplay projects remain on the user's computer.

The Beta is designed to allow existing work to remain available for opening and exporting while editing may be restricted until eligible account access is restored.

The trial expiry mechanism does not require deleting the user's local screenplay files.

---

# 12. Offline-First Behaviour

Kathana is designed to perform its core writing and local file operations on the user's computer.

An Internet connection may be required for certain account operations, including:

- authentication;
- requesting verification codes;
- entitlement checks;
- and other online account services.

The application does not require cloud screenplay storage in order to provide its normal local writing workflow.

---

# 13. Account and Screenplay Separation

A central architectural principle of this Beta is the separation between:

**Account information**

and

**Screenplay content.**

Account services may process information required for:

- authentication;
- Beta access;
- entitlement;
- acquisition information;
- Terms acceptance;
- support;
- and service administration.

Your normal screenplay-writing workflow does not require your screenplay to be uploaded to the account backend.

---

# 14. Privacy

Kathana Beta is designed with a local-first privacy model.

The Application does not operate as a cloud service for storing or synchronising screenplay files.

Users should understand that information can still be transmitted when they voluntarily use online services, contact support, participate in community services, or otherwise choose to provide information.

See:

[`Privacy Policy`](../../docs/PRIVACY.md)

for the complete public privacy documentation.

---

# 15. Help, Support and Community

The Beta provides separate paths for:

- documentation;
- technical support;
- account support;
- and community resources.

Official support:

**jagnaam.kathana.app@gmail.com**

Users are encouraged not to send screenplay files or confidential creative material to support unless necessary.

See:

[`Support Guide`](../../docs/SUPPORT.md)

for recommended support practices.

---

# 16. Security Architecture

The desktop application uses Electron security controls including:

- context isolation;
- disabled Node.js integration in the renderer;
- sandboxed renderer operation;
- controlled local application origin;
- restricted network access;
- and controlled `.kathana` file handling.

The application also restricts normal network access to the services required by its architecture.

These measures are intended to reduce unnecessary access between application components.

No software system can guarantee complete security.

Security issues should be reported privately to:

**jagnaam.kathana.app@gmail.com**

---

# 17. File and Creative-Work Responsibility

Kathana does not claim ownership of the screenplay content you create using the Application.

Subject to your own rights and any third-party material you choose to include, your creative work remains yours.

You are responsible for:

- maintaining backups;
- protecting your computer;
- protecting local project files;
- ensuring that imported material is legally usable;
- reviewing exported material;
- and maintaining any other records necessary for your creative or professional work.

---

# 18. Beta Status

This is a Beta release.

Users should expect that:

- features may change;
- interfaces may change;
- bugs may occur;
- compatibility may vary;
- account services may evolve;
- file-format behaviour may evolve;
- platform availability may expand;
- and future releases may not preserve every Beta behaviour.

Kathana Beta v0.1.0 should therefore not be treated as a guarantee of future functionality.

---

# 19. macOS Distribution and Gatekeeper

The current macOS Beta build is distributed for Apple Silicon.

The distributed macOS build is **not signed with a Developer ID Application certificate and is not notarized by Apple**.

As a result, macOS may display a security warning when the application is first opened.

This is a consequence of the current Beta distribution method and does not by itself indicate that the application has been modified after publication.

Users should obtain the application only from an official Kathana distribution channel and should verify the published SHA-256 checksum where appropriate.

Future releases may use a different signing and notarization process.

---

# 20. Release Integrity

A SHA-256 checksum is published with the macOS release.

For the current v0.1.0 Apple Silicon build:

**Filename:**

`Kathana-Beta-v0.1.0-mac-arm64.dmg`

**SHA-256:**

`ada4a88e68b8ade52bcbf2be21207bfc5a2215c44fbbf40cf8d25485a40d5e2f`

Users may calculate the SHA-256 checksum of their downloaded file and compare it with the published value.

A matching checksum confirms that the downloaded file has the same contents as the published release file.

---

# 21. Third-Party Software

Kathana incorporates and/or uses third-party software, libraries, fonts, frameworks, and services.

These include components used by the desktop application and its build/distribution environment.

Third-party components remain subject to their respective licences.

The applicable notices for this release are available at:

[`Third-Party Notices`](../../notices/THIRD-PARTY-NOTICES.md)

---

# 22. Public Documentation

The following documentation accompanies the Beta:

- [`User Guide`](../../docs/USER-GUIDE.md)
- [`Privacy Policy`](../../docs/PRIVACY.md)
- [`Terms and Conditions`](../../docs/TERMS.md)
- [`Support Guide`](../../docs/SUPPORT.md)
- [`Third-Party Notices`](../../notices/THIRD-PARTY-NOTICES.md)
- [`Changelog`](../../CHANGELOG.md)

---

# 23. Known Release Considerations

The following should be understood before installing this Beta:

### macOS security warning

The current macOS build is not Developer ID signed or notarized.

### Beta software

The application is an early public release and may contain defects.

### Import/export differences

Conversion between file formats may produce differences that require manual review.

### Backups

Kathana is not a replacement for an independent backup strategy.

### Online account services

Authentication and other account functions may require Internet access.

### Platform availability

The current public release provides a macOS Apple Silicon build. Other platforms may be published later.

---

# 24. Release Scope

Kathana Beta v0.1.0 establishes the public Beta foundation.

The release includes:

- the desktop writing environment;
- local screenplay projects;
- account authentication;
- Beta entitlement;
- local trial handling;
- public documentation;
- support infrastructure;
- third-party notices;
- release integrity information;
- and the public distribution structure.

Unreleased experiments, future features, internal development work, and private implementation details are not considered part of this public release unless explicitly included in the distributed application or documentation.

---

# 25. Publisher

Kathana Beta v0.1.0 is published by:

**JAGNAAM PICTURES**

Public product:

**Kathana**

---

# 26. Copyright

**© 2026 JAGNAAM PICTURES. All rights reserved.**

Kathana's proprietary software, branding, original visual identity, and original product materials remain protected by applicable intellectual-property rights.

Third-party software and assets remain subject to their respective licences.

---

### Where Stories find their form.

**JAGNAAM PICTURES**