<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" width="600" height="120" viewBox="0 0 600 120">
  <rect width="600" height="120" fill="#0d1117"/>
  <circle cx="60" cy="60" r="35" fill="none" stroke="#7c3aed" stroke-width="3"/>
  <circle cx="60" cy="60" r="20" fill="none" stroke="#a855f7" stroke-width="2"/>
  <circle cx="60" cy="60" r="6" fill="#c084fc"/>
  <text x="110" y="45" font-family="monospace" font-size="28" font-weight="bold" fill="#ffffff">cosmix-extensions</text>
  <text x="112" y="75" font-family="monospace" font-size="13" fill="#7c3aed">community streaming extensions for cosmix</text>
</svg>

[

![Extensions](https://img.shields.io/badge/Platform-Cosmix-7c3aed?style=flat-square)

](https://github.com/cosmix-app/cosmix)
[

![License](https://img.shields.io/badge/License-GPL--3.0-red?style=flat-square)

](LICENSE)
[

![Template](https://img.shields.io/badge/Build%20With-CsxApi-blue?style=flat-square)

](https://github.com/cosmix-app/cosmix-extension-template)

</div>

---

## What are Extensions?

Extensions add streaming sources to the Cosmix app.
Each extension is a `.csx` file built from Kotlin code
using the official [cosmix-gradle-plugin](https://github.com/cosmix-app/cosmix-gradle-plugin).

---

## Build Your Own Extension

```kotlin
class MyProvider : CsxApi() {
    override val name = "My Extension"
    override val mainUrl = "https://example.com"
    override val lang = "en"

    override suspend fun search(query: String): List<SearchResult> { ... }
    override suspend fun load(url: String): LoadResponse { ... }
    override suspend fun getVideoSource(url: String): VideoSource { ... }
}

1. Fork the template
2. Extend CsxApi() and write your scraping logic
3. Push to GitHub — Actions will build your .csx file automatically

## Contributing

Want to add your extension here? Open a Pull Request with:
- Extension name
- Repository URL
- Supported language
- Status

## Guidelines

- Extensions must be open source
- No malware or harmful content
- Must use CsxApi() base class
- Must build successfully with cosmix-gradle-plugin

## ⚠️ Disclaimer

Cosmix and cosmix-extensions are not responsible for
any third-party extensions outside this organization.
Third-party extensions are built and maintained by
independent developers. Installing extensions from
unknown sources is entirely at your own risk.
We do not review, verify, or endorse any extension
that is not officially hosted under this organization.
Any damage, data loss, or legal issue caused by
third-party extensions is solely the responsibility
of the user.

## License

GPL-3.0 © 2026 Cosmix
