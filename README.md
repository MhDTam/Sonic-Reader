<p align="center"><img src="docs/images/banner.svg" alt="Sonic Reader — Read. Mark. Remember." width="100%"></p>

<p align="center"><strong>A focused Android workspace for documents, reading and ideas.</strong></p>
<p align="center"><a href="README.ar.md">العربية</a> · <strong>English</strong> · <a href="https://github.com/MhDTam/Sonic-Reader/releases/latest">Download</a> · <a href="https://github.com/MhDTam/Sonic-Reader/issues/new/choose">Report a problem</a></p>

**Android 7.0+** · **Arabic & English** · **Offline PDF reading** · **Proprietary application**

Sonic Reader brings your documents, annotations and page-linked notes into one calm workspace. Read a PDF, mark an idea, and return to the exact page when you need it.

This is the official **downloads and documentation** repository. The application's source code is private and is not published here.

## A look inside

| Your library | Focused reading | Notes tied to the page |
| :---: | :---: | :---: |
| <img src="docs/images/library-en.png" alt="Document library with demonstration PDFs" width="240"> | <img src="docs/images/reader-en.png" alt="PDF reader with its annotation toolbar" width="240"> | <img src="docs/images/notes-en.png" alt="Notes connected to demonstration document pages" width="240"> |

All screenshots use synthetic demonstration documents. [See the Arabic interface and more screens →](docs/SCREENSHOTS.md)

## What you can do

- **Read comfortably:** continuous PDF reading, zoom, search, page navigation and reading-position memory.
- **Keep the page steady:** show or hide both reading toolbars with a smooth transition that preserves your scroll position and zoom.
- **Work with text:** select Arabic and English text, copy passages and highlight useful ideas. Online translation is available when requested.
- **Annotate your documents:** pen, shapes, text, highlights, underlines, sticky notes and signatures.
- **Build a notebook:** keep notes and bookmarks connected to their document and page; search and export them.
- **Make the workspace yours:** Arabic/RTL and English/LTR interfaces, multiple themes, favorites and library views.

## Download and install

1. Open [the latest release](https://github.com/MhDTam/Sonic-Reader/releases/latest).
2. Download **`Sonic-Reader-1.0.0-16131.apk`** from **Assets**.
3. Open the APK on an Android device running **Android 7.0 or newer**. Android may ask you to allow installation from the browser or file manager you chose.

The universal APK includes **arm64-v8a**, **armeabi-v7a** and **x86_64**. A `SHA256SUMS.txt` file accompanies the release for integrity verification.

Public releases have their own signing identity. Development/preview builds signed with another key cannot be updated in place. If Android reports a signature conflict, preserve/export your documents and notes before changing installations.

## Online features, clearly separated

PDF reading, local annotations and notes work offline. **Translation** sends the selected text to Google when you request it. **Optional cloud Office conversion** sends a chosen document to the conversion service you configure, after the app's cloud-upload consent. It requires that service's own access credentials and internet access.

The public APK includes **no private conversion endpoint, account, or access token**. Cloud conversion is disabled by default. Basic local conversion is available for supported DOCX, XLSX and PPTX content; layout fidelity varies by document. The public release does not include a hosted conversion-service subscription or guarantee.

[Read the privacy information →](PRIVACY.md)

## Feedback and support

Use [GitHub Issues](https://github.com/MhDTam/Sonic-Reader/issues/new/choose) for reproducible bugs, usability feedback and translation suggestions. Include your Android version, app build number and steps to reproduce.

Please use a synthetic sample and redact screenshots. **Do not post private documents, passwords, access tokens, or personal account information.**

## Rights and credits

Copyright © 2026 [MhDTam](https://github.com/MhDTam). All rights reserved.

Sonic Reader is **closed-source, proprietary software**. Publishing its official APK and documentation does not release the application source code or grant an open-source license. See [LICENSE.md](LICENSE.md).

Third-party libraries and fonts retain their own licenses and rights. Font credits include **IBM Plex Sans Arabic (IBM)**, the included **Microsoft font families and their respective rights holders**, and **Thmanyah Serif (ثمانية)**. See [third-party notices](THIRD_PARTY_NOTICES.md) and the full notices supplied with each release.

## Release notes

[1.0.0 · build 16131](docs/CHANGELOG.md) — bilingual public-distribution edition with steady reading controls, improved mixed-script selection and no private cloud-service configuration.
