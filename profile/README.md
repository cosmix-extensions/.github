# Cosmix Extensions

Official extension repository for the [Cosmix](https://github.com/cosmix-app/cosmix) streaming app.

## What are Extensions?

Extensions (.csx files) add streaming sources to the Cosmix app.
Each extension is maintained in its own repository and built
automatically using GitHub Actions.

## Available Extensions

| Extension | Language | Status |
|-----------|----------|--------|
| [AnimeDekho](https://github.com/cosmix-extensions/AnimeDekho) | Hindi | ✅ Active |

## How to Install Extensions

1. Open Cosmix app
2. Go to Settings → Extensions
3. Add repository URL
4. Install any extension from the list

## Build Your Own Extension

Use the official template to build your own extension:
[cosmix-extension-template](https://github.com/cosmix-app/cosmix-extension-template)

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

## License

GPL-3.0 © 2026 Cosmix
