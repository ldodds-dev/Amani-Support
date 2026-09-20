# ΛMΛNI Support

> **Built for Speed, Privacy, and Simplicity.**

Welcome to the official public support hub for **ΛMΛNI**, browser and search platform.

[![Website](https://img.shields.io/badge/website-amani--browser.com-orange)](https://amani-browser.com)
[![Version](https://img.shields.io/badge/version-v0.2.0-orange)](https://amani-browser.com)
![Status](https://img.shields.io/badge/status-Active%20Beta-D4AF37)
![Platforms](https://img.shields.io/badge/platforms-macOS%20ARM64%20%7C%20Windows%20x64%20%7C%20Linux%20AMD64-blue)
[![Support](https://img.shields.io/badge/support-Open%20an%20Issue-2EA44F)](https://github.com/ldodds-dev/Amani-Support/issues/new)

Use this repository to report bugs, request improvements, document compatibility problems, and get help with ΛMΛNI on macOS, Windows, Linux, and the web.

> [!IMPORTANT]
> ΛMΛNI is Beta software. Features, interfaces, compatibility, and system requirements may change as the product develops.

## What this repository supports

You may open an issue for:

- Installation, startup, update, or uninstall problems
- macOS, Windows, or Linux compatibility
- Website and desktop-browser behavior
- Search, suggestions, and result-page problems
- Ghost Mode behavior and privacy-related interface concerns
- Downloads and installer-link problems
- World Time, globe controls, city information, and time-zone display
- Maps, geolocation, GPS permissions, route planning, and navigation UI
- Visual, responsive-layout, mobile, keyboard, or accessibility problems
- Feature requests and usability suggestions
- Documentation corrections

This repository is intended for support and feedback. It does not provide public access to AMANI's private development source code, internal infrastructure, credentials, or operational systems.

## Before opening an issue

Please complete these checks first:

1. Confirm that you are using the most recent ΛMΛNI Beta available from [amani-browser.com](https://amani-browser.com).
2. Restart ΛMΛNI and, when appropriate, restart your device.
3. Search the [existing issues](https://github.com/ldodds-dev/Amani-Support/issues) to see whether the problem has already been reported.
4. Test whether the problem occurs consistently or only under a particular network, device, location, or account condition.
5. Remove personal or sensitive information from screenshots, logs, addresses, searches, and filenames.

If an existing issue describes the same problem, add any new reproduction details there instead of opening a duplicate.

## How to report a bug

Open a [new issue](https://github.com/ldodds-dev/Amani-Support/issues/new) and include as much of the following information as possible.

### Required information

- **Short summary:** A clear description of the problem
- **ΛMΛNI version:** For example, `0.2.0-beta.2`
- **Environment:** Website or desktop application
- **Operating system:** Include the version and architecture when known
- **Device:** Computer, phone, or tablet model when relevant
- **Affected feature:** Search, Ghost Mode, Downloads, World Time, Maps, navigation, or another area
- **Steps to reproduce:** Numbered steps beginning before the problem appears
- **Expected result:** What you believed should happen
- **Actual result:** What happened instead
- **Frequency:** Always, often, sometimes, or once
- **Regression:** Whether the feature worked in an earlier AMANI version

### Helpful evidence

- Screenshot or short screen recording
- Exact error message
- Approximate date and time of the incident, including time zone
- Browser console error or application log, after sensitive information is removed
- Whether extensions, VPN software, security software, or network restrictions were active
- Whether the problem also occurs in a new window or after restarting AMANI

### Suggested bug-report format

```markdown
## Summary
A concise explanation of the problem.

## Environment
- ΛMΛNI version:
- Website or desktop:
- Operating system:
- Device/architecture:
- Network type, if relevant:

## Steps to reproduce
1.
2.

## Expected behavior
What should have happened?

## Actual behavior
What happened instead?

## Frequency
Always / Often / Sometimes / Once

## Additional context
Screenshots, sanitized logs, error messages, or other useful information.
```

## Feature requests

Feature requests are welcome. Please describe:

- The problem or limitation you are trying to solve
- The user experience you would like to see
- Why the change would be useful
- Which platform or ΛMΛNI feature it affects
- Any privacy, accessibility, mobile, or compatibility considerations

Please focus on the desired outcome rather than requiring one particular technical implementation.

## Installation and download support

ΛMΛNI Beta installers are currently provided for:

| Platform | Architecture | Package |
| --- | --- | --- |
| macOS | Apple Silicon / ARM64 | `.dmg` |
| Windows | x64 | Setup `.exe` |
| Linux | AMD64 / x64 | `.deb` |

Download AMANI only through [amani-browser.com](https://amani-browser.com) or another location explicitly identified there as official.

When reporting an installer problem, include:

- The installer filename
- File size, if available
- Where the file was downloaded
- The exact operating-system warning or error
- Whether the download completed successfully
- Whether a previous AMANI installation was already present

### Platform notes

#### macOS

Apple may prevent an application from opening when its developer signature or notarization cannot be verified. If macOS reports that AMANI is damaged, unidentified, or cannot be opened, do not disable system security or use third-party bypass instructions. Confirm that the installer came from the official AMANI website and report the exact warning here.

#### Windows

Windows SmartScreen or security software may display a reputation or publisher warning for a Beta installer. Confirm the download source and report the complete warning text. Do not disable antivirus or endpoint protection solely to install AMANI.

#### Linux

Include your distribution, release version, desktop environment, and the full package-manager error. The current Linux Beta is distributed as an AMD64 `.deb` package and may not install directly on non-Debian-based distributions or ARM systems.

## Feature-specific reporting

### Ghost Mode

For Ghost Mode issues, explain:

- Whether the problem occurs in the website, desktop browser, or both
- Whether a new Ghost Mode window opens
- Whether history or session data remains after all Ghost Mode windows close
- Whether the problem affects the background, search bar, disclaimer, tabs, or controls

Ghost Mode is available on desktop version only. 
Do not include private browsing history or sensitive search content in a public issue.

### World Time

For World Time issues, include:

- City, country, or time zone searched
- Displayed local time and expected local time
- 12-hour or 24-hour mode
- Whether daylight-saving time appears incorrect
- Whether the globe, zoom, reset, time-shift, labels, or city selection is affected

### Maps and navigation

For Maps or navigation issues, include:

- Starting area and destination at a safe level of detail
- Whether location permission was granted
- Device and browser/desktop environment
- Whether GPS location, route calculation, rerouting, zoom, filters, or spoken guidance is affected
- Whether the device had an active network connection

> [!WARNING]
> ΛMΛNI navigation features are under active development. Do not rely on Beta navigation as the sole source of safety-critical, emergency, road-closure, traffic, or routing information. Always follow posted signs, applicable law, and real-world conditions.

## Privacy when requesting support

GitHub issues in this repository are public. Before posting, remove or obscure:

- Passwords, tokens, API keys, cookies, and authentication headers
- Email addresses, phone numbers, and account identifiers
- Home, school, workplace, or precise location information
- Search terms or browsing history you do not want made public
- Full navigation origins, destinations, or GPS coordinates
- Personal filenames, profile names, serial numbers, and device identifiers
- Information belonging to another person

AMANI maintainers may ask for additional diagnostic information. Share only what is necessary to reproduce the issue, and continue to redact sensitive data.

## Security vulnerabilities

**Do not report a security vulnerability, exploit, credential exposure, or privacy-sensitive weakness in a public issue.** Public disclosure before a fix is available can place users at risk.

Use GitHub's private vulnerability-reporting option through the repository's **Security** page when that option is available. If private reporting is unavailable, open a minimal public issue requesting a private security contact **without including technical exploit details, secrets, personal data, or reproduction material**.

Security reports should identify:

- Affected ΛMΛNI version and platform
- The type and potential impact of the vulnerability
- Whether exploitation requires local access, user interaction, or authentication
- Reproduction details provided only through the private reporting channel
- Any known mitigations

Please allow a reasonable period for investigation and remediation before publishing vulnerability details.

## Support workflow

New reports generally move through the following stages:

1. **Triage** — Confirm the report contains enough information.
2. **Reproduction** — Attempt to reproduce the behavior in a supported environment.
3. **Classification** — Identify whether it is a bug, compatibility issue, feature request, documentation issue, or external-service problem.
4. **Prioritization** — Consider severity, user impact, privacy, security, and reproducibility.
5. **Resolution** — Implement a fix, document a workaround, request more information, or close the report with an explanation.

Submitting an issue does not guarantee a specific implementation or response time. AMANI is actively developed, and priorities may change as the Beta evolves.

## Community guidelines

To keep support useful and welcoming:

- Be respectful and describe the technical behavior rather than blaming individuals.
- Keep each issue focused on one problem or request.
- Do not post spam, advertisements, unrelated promotions, or duplicate reports.
- Do not publish confidential information, personal attacks, or another person's private data.
- Do not use support issues to request access to private repositories, credentials, internal infrastructure, or user data.
- Follow GitHub's applicable terms and community standards.

Issues may be edited, locked, or closed when they expose sensitive data, create security risk, duplicate an existing report, lack actionable information, or fall outside AMANI support.

## Frequently asked questions

### Is ΛMΛNI production-ready?

AMANI is currently in Beta. It is available for evaluation and feedback while features, compatibility, packaging, and documentation continue to mature.

### Where should I download ΛMΛNI?

Use [amani-browser.com](https://amani-browser.com). Avoid installers shared through unofficial mirrors, messages, or third-party download sites.

### Can I post screenshots or logs?

Yes, when they are relevant and thoroughly redacted. Review the entire image or file for personal information, searches, URLs, credentials, and location data before uploading it.

### Why was my issue closed?

Common reasons include duplication, insufficient reproduction information, unsupported hardware or operating systems, expected Beta behavior, an external-provider problem, or inactivity after additional information was requested.

### Does opening an issue provide private customer support?

No. GitHub issues are public conversations. Do not include confidential or personally identifying information.

## Acknowledgment

Thank you for helping improve AMANI. Clear, reproducible reports make it easier to identify problems, prioritize fixes, and build a more dependable privacy-focused browsing experience.

---

<img width="538" height="65" alt="Screenshot 2026-09-19 at 8 33 06 PM" src="https://github.com/user-attachments/assets/e549ab9c-29ff-4416-859f-ce335ebc359e" />
