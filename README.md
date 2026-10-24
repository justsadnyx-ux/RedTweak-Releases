# RedTweak — Official Releases

This repository distributes **compiled binaries only**.

RedTweak is **closed source**; the source code is maintained privately and is not
published here (or anywhere else). This repository exists solely so that users can
download verified builds and so the built-in updater can reach the GitHub Releases API.

## Download

| Version | Platform | File |
| ------- | -------- | ---- |
| 1.0.0   | Windows 10/11 x64 | `RedTweak.exe` |

Grab the latest from the [Releases](../../releases/latest) page.

## Verify your download

Every release ships a `SHA256SUMS.txt`. Verify in PowerShell:

```powershell
Get-FileHash .\RedTweak.exe -Algorithm SHA256
Get-Content .\SHA256SUMS.txt
```

The hashes must match exactly.

## Update system

RedTweak checks this repository's latest release through the public GitHub API and
compares the release tag against its own version. If a newer build exists, the app
shows the release notes and can download `RedTweak.exe` directly.

No account, token, or telemetry is involved.

## License

RedTweak is proprietary freeware. See [LICENSE](LICENSE).

## Links

- Website: https://redtweak.vercel.app
- Issues: use the website contact page
