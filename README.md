[![](https://img.shields.io/nuget/v/soenneker.clamav.freshclam.linux.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.clamav.freshclam.linux/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.clamav.freshclam.linux/build-and-test.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.clamav.freshclam.linux/actions/workflows/build-and-test.yml)
[![](https://img.shields.io/nuget/dt/soenneker.clamav.freshclam.linux.svg?style=for-the-badge)](https://www.nuget.org/packages/soenneker.clamav.freshclam.linux/)
[![](https://img.shields.io/github/actions/workflow/status/soenneker/soenneker.clamav.freshclam.linux/codeql.yml?style=for-the-badge)](https://github.com/soenneker/soenneker.clamav.freshclam.linux/actions/workflows/codeql.yml)

# Soenneker.Clamav.Freshclam.Linux

The official ClamAV FreshClam runtime packaged for Linux x64 .NET applications.

## Installation

```bash
dotnet add package Soenneker.Clamav.Freshclam.Linux
```

The package copies its runtime beneath `Resources/linux-x64/freshclam/`. Most applications should reference `Soenneker.Clamav.Freshclam.Util`, which selects the platform and provides the managed update API.

## Licensing and source

The package scaffolding is MIT-licensed. The bundled ClamAV runtime is GPL-2.0-only and preserves its upstream `COPYING.txt`, third-party notices, and exact release provenance in `SOURCE.txt`.
