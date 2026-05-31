# 🌌 cosmix-extensions

**Community streaming extensions for the Cosmix app**

[

![Platform](https://img.shields.io/badge/Platform-Cosmix-7c3aed?style=for-the-badge)

](https://github.com/cosmix-app/cosmix)
[

![License](https://img.shields.io/badge/License-GPL--3.0-red?style=for-the-badge)

](LICENSE)
[

![Template](https://img.shields.io/badge/Built%20With-CsxApi-blue?style=for-the-badge)

](https://github.com/cosmix-app/cosmix-extension-template)

---

## What are Extensions?

Extensions add streaming sources to the Cosmix app. Each extension is a `.csx` file built from Kotlin code using the official [cosmix-gradle-plugin](https://github.com/cosmix-app/cosmix-gradle-plugin).

---

## Build Your Own Extension

1. Fork [cosmix-extension-template](https://github.com/cosmix-app/cosmix-extension-template)
2. Extend `CsxApi()` and write your scraping logic
3. Push to GitHub — Actions will build your `.csx` automatically

---

## Contributing

Want your extension listed? Open a Pull Request with:
- Extension name and repository URL
- Supported language and region
- Active maintenance confirmation

---

## Guidelines

- Extensions must be open source
- No malware or harmful content
- Must use `CsxApi()` base class
- Must build successfully with `cosmix-gradle-plugin`

---

## ⚠️ Disclaimer

> Cosmix and cosmix-extensions are not responsible for any third-party extensions outside this organization. Third-party extensions are built and maintained by independent developers. Installing extensions from unknown sources is entirely at your own risk. We do not review, verify, or endorse any extension that is not officially hosted under this organization. Any damage, data loss, or legal issue caused by third-party extensions is solely the responsibility of the user.

---

*GPL-3.0 © 2026 Cosmix Extensions*
