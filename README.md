# Yith Releases

Official public release distribution for **Yith — Forensic Equity Research Terminal**.

Yith is a local-first desktop workspace for researching financial filings and earnings transcripts. It provides document ingestion, matrix-based multi-document synthesis, forensic redlining, guidance and Q&A ledgers, transcript tone analysis, local SQLite storage, and optional permissive open-weights local AI.

> This repository distributes desktop builds. The source repository is maintained separately.

## Downloads

Visit [**Releases**](https://github.com/Crystal-gazer/Yith-releases/releases) to download the latest Yith installer or portable package.

Release artifacts may include:

| Platform | Common artifact formats |
|---|---|
| Windows | `.msi`, `.exe` |
| macOS | `.dmg`, `.zip` |
| Linux | `.AppImage`, `.deb` |

Formats vary by release and platform support.

## Installation

1. Open the [latest release](https://github.com/Crystal-gazer/Yith-releases/releases/latest).
2. Download the artifact for your operating system and architecture.
3. Verify the checksum or release signature when one is provided.
4. Run the installer or extract the package and launch Yith.
5. Review your operating system's application security prompt when opening a newly downloaded desktop application.

### macOS

Open the `.dmg`, drag Yith to Applications, and launch it from Applications. If Gatekeeper displays a security warning, review the downloaded application's signature and provenance before proceeding.

### Windows

Run the `.msi` or `.exe` installer and follow the setup prompts. Keep Windows protected by downloading only release artifacts published in this repository.

### Linux

Install the `.deb` package using your distribution's package manager, or set the `.AppImage` executable and run it locally. AppImage requirements vary by desktop environment and distribution.

## Local data and privacy

Yith is designed as a local-first desktop application:

- Research documents remain on the user's device unless the user explicitly chooses to export or share them.
- Workspace data is stored locally.
- AI can operate in a no-AI deterministic mode or with compatible local/open-weights models.
- Any external network activity should be explicitly expected by the user, such as downloading models or checking for updates.

Review the privacy policy and EULA included with a release before use.

## Security and integrity

- Download release artifacts only from this repository's **Releases** page.
- Do not run executables received through unofficial mirrors or unsolicited attachments.
- Prefer releases that publish checksums or cryptographic signatures.
- Verify that the artifact's filename, platform, and architecture match your system.

If a checksum or signature is provided, verify it after download and before installation.

## Updating

Download and install a newer release from [this repository's Releases page](https://github.com/Crystal-gazer/Yith-releases/releases). Back up locally important research data before major upgrades.

## Compatibility

System requirements and supported platforms are listed in the assets and notes for each specific release. Requirements may change between versions.

## Support

Please report issues only in the release repository when they concern:

- Download availability
- Installer or packaging problems
- Release artifacts or checksums
- Upgrade or platform compatibility problems

Include the Yith version, operating system, architecture, installer format, and relevant error messages without attaching confidential documents or local database files.

## Disclaimer

Yith is research software, not investment advice. Filing analysis, extracted guidance, classifications, and AI-generated interpretations may contain errors or omit context. Verify important conclusions against original filings and transcripts.
