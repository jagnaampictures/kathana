# KATHANA — BETA v0.1.0 THIRD-PARTY NOTICES

**Version:** 0.1.0  
**Release:** Kathana Beta v0.1.0  
**Release period:** October 2026  
**Publisher:** JAGNAAM PICTURES

---

## 1. Purpose of This Notice

Kathana Beta v0.1.0 incorporates, bundles, links to, or is built using software, libraries, fonts, frameworks, and services created by third parties.

These components are not owned by JAGNAAM PICTURES merely because they are used by Kathana.

Each third-party component remains subject to its applicable licence, copyright notice, attribution requirements, and other applicable terms.

This document identifies the principal third-party components relevant to the Beta release and is intended to accompany the public distribution of Kathana Beta v0.1.0.

Where a component's own licence or notice imposes requirements beyond the summary provided here, the component's original licence and notice take precedence.

---

# 2. Kathana Proprietary Material

The following are part of Kathana's own product and are not released under an open-source licence by this notice:

- Kathana application code;
- Kathana application architecture and original implementation;
- Kathana user interface;
- Kathana product name;
- Kathana logo and product branding;
- Kathana original visual assets;
- Kathana documentation;
- Kathana website content;
- original Kathana product copy;
- original Kathana screenplay-formatting implementation;
- and other original materials created for Kathana.

Unless expressly stated otherwise:

**© 2026 JAGNAAM PICTURES. All rights reserved.**

This third-party notice does not grant permission to copy, modify, redistribute, reverse engineer, rebrand, or commercially exploit Kathana proprietary material.

---

# 3. Summary of Third-Party Components

The Beta release uses or is associated with the following principal third-party components.

| Component | Role | Licence / Terms |
|---|---|---|
| Electron | Desktop application runtime | MIT |
| Chromium | Browser/runtime technology included through Electron | Chromium/BSD and other applicable open-source licences |
| Node.js | Runtime/tooling component used by Electron and development environment | MIT |
| V8 | JavaScript engine used through Electron/Chromium | BSD-style and other applicable licences |
| HarfBuzz | Text shaping | MIT |
| HarfBuzz WebAssembly build | Text shaping for browser/application text rendering | MIT, together with applicable bundled dependency notices |
| Supabase JavaScript client | Account/authentication communication | MIT |
| Electron Builder | Application packaging/build tooling | MIT |
| esbuild | JavaScript bundling/build tooling | MIT |
| Courier Prime | Bundled typeface | SIL Open Font License 1.1 |
| Inter | Bundled typeface | SIL Open Font License 1.1 |
| Noto Sans family components | Bundled typefaces for Indian scripts and multilingual text | SIL Open Font License 1.1 |
| GitHub | Public repository/release hosting | GitHub service terms |
| Supabase | Account/backend service | Supabase service terms |
| Google Fonts | Website font delivery | Google Fonts terms/licensing applicable to individual fonts |

The exact dependency tree may contain additional transitive components. Package-level licence information should be consulted when reproducing or redistributing individual dependencies.

---

# 4. Electron

Kathana Beta v0.1.0 is distributed as an Electron desktop application.

Electron combines Chromium, Node.js, and related technologies for desktop application development.

**Licence:** MIT

Electron and its included third-party technologies remain subject to their respective licences and notices.

Electron's trademarks and branding are not part of the Kathana trademark or brand identity.

---

# 5. Chromium

Electron incorporates Chromium technology.

Chromium is distributed under open-source licences, including BSD-style licensing and licences applicable to individual Chromium dependencies.

Chromium contains numerous third-party components, each of which may have its own copyright and licence requirements.

Kathana does not claim ownership of Chromium or its third-party components.

Electron's and Chromium's applicable notices should be consulted when redistributing Electron-derived software.

---

# 6. Node.js

Node.js is used as part of the Electron environment and development/build ecosystem.

**Licence:** MIT

Node.js is an independent open-source project and is not owned by JAGNAAM PICTURES.

---

# 7. V8

V8 is the JavaScript engine used by Chromium and Electron.

V8 is distributed under open-source licensing, including BSD-style licensing and associated third-party notices.

Kathana does not claim ownership of V8.

---

# 8. HarfBuzz

Kathana uses HarfBuzz technology for text shaping.

HarfBuzz is important for correctly processing complex scripts and multilingual text, including scripts where a visible character may be composed from multiple Unicode elements.

**HarfBuzz licence:** MIT

The applicable HarfBuzz copyright and licence notice is included with the relevant software distribution.

Kathana does not claim ownership of HarfBuzz.

---

# 9. HarfBuzz WebAssembly

The Kathana application includes a WebAssembly build of HarfBuzz used for text shaping.

The distributed build is based on:

**HarfBuzz 14.5.0**

The applicable HarfBuzz licensing terms remain in force for the distributed component.

The WebAssembly build may incorporate dependencies and generated/runtime components whose licensing terms must also be respected when independently redistributing or modifying that component.

---

# 10. musl libc

Where applicable to the distributed WebAssembly/runtime components, musl libc is an open-source component used in the relevant software environment.

**Licence:** MIT

Kathana does not claim ownership of musl libc.

The applicable copyright and licence notice should be retained when the component is redistributed independently.

---

# 11. Emscripten

Emscripten is part of the toolchain commonly used to compile C/C++ software to WebAssembly and may be relevant to the build process for WebAssembly components used by Kathana.

Emscripten and its associated components are distributed under applicable open-source licences, including the MIT licence and the University of Illinois/NCSA Open Source License for relevant components.

Kathana does not claim ownership of Emscripten.

The licensing terms of individual Emscripten components must be respected when they are independently redistributed.

---

# 12. Supabase JavaScript Client

Kathana uses the Supabase JavaScript client for communication with its account/backend services.

**Package:** `@supabase/supabase-js`

**Release used for this Beta:** `2.117.3`

**Licence:** MIT

In Kathana Beta v0.1.0, Supabase is used for account-related functionality such as authentication and entitlement-related services.

The Supabase client does not change Kathana's local-first screenplay architecture.

Kathana does not use Supabase as its routine cloud storage location for `.kathana` screenplay files.

---

# 13. Supabase Service

Kathana Beta uses a Supabase-hosted backend for account-related services.

This is a third-party hosted service rather than a component owned by JAGNAAM PICTURES.

The service may process account information required for authentication, entitlement, acquisition information, Terms acceptance, and related account administration.

The Kathana privacy documentation explains the relationship between account information and screenplay content.

---

# 14. Electron Builder

Electron Builder is used to package Kathana desktop releases.

**Licence:** MIT

Electron Builder is a build/distribution tool and is not part of Kathana's proprietary product identity.

---

# 15. esbuild

esbuild is used to bundle JavaScript required by the application, including the Supabase client integration.

**Licence:** MIT

Kathana does not claim ownership of esbuild.

---

# 16. Fonts

Kathana Beta includes fonts and/or font families used to provide a readable writing environment and multilingual script support.

These include:

- Courier Prime;
- Inter;
- Noto Sans family components;
- Noto Sans Kannada;
- Noto Sans Devanagari;
- Noto Sans Tamil;
- Noto Sans Telugu;
- Noto Sans Malayalam;
- Noto Sans Bengali;
- Noto Sans Gujarati;
- Noto Sans Gurmukhi;
- Noto Sans Oriya;
- and other applicable Noto Sans components included with the Beta.

The relevant Noto Sans and other bundled font files are generally distributed under the:

**SIL Open Font License, Version 1.1 (OFL-1.1)**

Courier Prime and Inter are also distributed under the SIL Open Font License 1.1.

Font files remain subject to their individual copyright and licence terms.

---

# 17. SIL Open Font License 1.1

The SIL Open Font License permits the use, study, modification, and redistribution of licensed fonts subject to its conditions.

Important conditions can include:

- preservation of copyright and licence notices;
- compliance with the Reserved Font Name provisions where applicable;
- and the requirement that fonts themselves not be distributed under a more restrictive licence.

The OFL does not transfer ownership of the font to Kathana or JAGNAAM PICTURES.

The original font licence should be consulted before independently redistributing or modifying bundled fonts.

---

# 18. Reserved Font Names

Some fonts distributed under the SIL Open Font License may specify Reserved Font Names.

Where a bundled font includes Reserved Font Names, modifications and redistribution must follow the applicable OFL requirements.

Kathana does not claim ownership of any Reserved Font Name.

---

# 19. Website Fonts

Kathana's website may use additional fonts that are separate from the fonts bundled directly into the desktop application.

Website font usage does not automatically mean that the same font is included in the desktop application.

Website fonts may be delivered through services such as Google Fonts and remain subject to the licence terms applicable to each individual typeface.

---

# 20. Google Fonts

The Kathana website may use Google Fonts for web typography.

Google Fonts is a third-party service.

Individual fonts distributed through Google Fonts are generally licensed under open-source font licences, commonly including the SIL Open Font License.

The licence applicable to an individual font should be checked before independently redistributing that font.

Kathana does not claim ownership of Google Fonts or the individual typefaces provided through the service.

---

# 21. GitHub

GitHub is used for public repository, documentation, and release distribution infrastructure.

GitHub is an independent third-party service.

The availability of Kathana files through GitHub does not grant GitHub ownership of Kathana's proprietary software or branding.

Use of GitHub is subject to GitHub's applicable service terms.

---

# 22. Screenplay Content

Kathana is a writing application.

Third-party notices do not alter the ownership of screenplay material created by users.

Kathana does not claim ownership of a user's original screenplay merely because the screenplay was created, edited, imported, or exported using Kathana.

Users remain responsible for ensuring that material they import, reproduce, publish, or otherwise use is legally available to them.

---

# 23. User-Chosen Fonts

Kathana users may choose fonts available on their own systems or otherwise accessible to the application.

A font being selectable or displayed by Kathana does not mean that JAGNAAM PICTURES owns or redistributes that font.

The licence governing a user-installed font remains the responsibility of its respective copyright holder and user.

---

# 24. Third-Party Services vs. Bundled Software

For clarity, the following categories are different:

### Bundled software

Software and assets physically distributed as part of the Kathana application package.

Examples include applicable fonts, HarfBuzz components, and software included through the Electron runtime.

### Build-time software

Software used to create or package Kathana but not necessarily distributed as part of the application.

Examples include:

- Electron Builder;
- esbuild;
- Node.js development tooling.

### Hosted services

Services used by Kathana but operated by third parties.

Examples include:

- Supabase;
- GitHub;
- Google Fonts delivery infrastructure where applicable.

The presence of a third-party service in Kathana's architecture does not mean that the service receives screenplay content by default.

---

# 25. Trademarks

Names such as:

- Electron;
- Chromium;
- Node.js;
- V8;
- HarfBuzz;
- Supabase;
- GitHub;
- Google;
- Noto;
- Inter;
- Courier Prime;

and other third-party names and marks remain the property of their respective owners.

They are referenced solely for identification and attribution.

No trademark licence is granted by this document.

---

# 26. Licence Texts

Where practical, the public Kathana distribution should retain or provide access to the applicable licence texts and notices for third-party components.

At minimum, users redistributing relevant third-party components should preserve the applicable:

- copyright notices;
- licence notices;
- attribution notices;
- and other legally required notices.

The absence of a full licence text in this summary does not remove the obligations of the original licence.

---

# 27. Source and Dependency Information

Kathana's private source repository may contain package manifests and dependency-lock information used to establish the software environment for the Beta.

The public Kathana distribution is not a public source-code release.

The existence of an open-source dependency within Kathana does not mean that Kathana itself is open source.

Open-source components retain their own licences while Kathana's original proprietary components remain proprietary.

---

# 28. No Blanket Licence

Nothing in this document should be interpreted as granting a blanket licence to:

- Kathana source code;
- Kathana branding;
- Kathana artwork;
- Kathana documentation;
- JAGNAAM PICTURES intellectual property;
- or other proprietary Kathana material.

Permission to use a particular open-source dependency comes from that dependency's own licence.

---

# 29. Licence Compliance

JAGNAAM PICTURES intends to preserve applicable third-party copyright and licensing information accompanying the Beta.

If you believe that a third-party notice, attribution, copyright statement, or licence requirement relevant to the distributed Beta has been omitted or incorrectly identified, please contact:

**jagnaam.kathana.app@gmail.com**

Please identify the component and the relevant licensing information so the notice can be reviewed.

---

# 30. Relationship to Kathana Terms and Privacy Policy

This document concerns third-party software, fonts, libraries, frameworks, and services.

It does not replace:

- the Kathana Terms and Conditions;
- the Kathana Privacy Policy;
- the Kathana Support Guide;
- or other official Kathana documentation.

Those documents govern their respective subjects.

---

# 31. Release Identification

These notices apply to:

**Kathana Beta v0.1.0**

Current public desktop platform:

**macOS — Apple Silicon (arm64)**

Release artifact:

`Kathana-Beta-v0.1.0-mac-arm64.dmg`

---

# 32. Publisher

**JAGNAAM PICTURES**

Kathana

### Where Stories find their form.

---

**© 2026 JAGNAAM PICTURES. All rights reserved.**

Third-party software, fonts, libraries, frameworks, services, trademarks, and other referenced materials remain the property of their respective owners and are governed by their applicable licences or terms.