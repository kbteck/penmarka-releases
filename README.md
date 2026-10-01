# Penmarka downloads

This repository only hosts the official installer for
[Penmarka](https://penmarka.com), the screen annotation app for Windows.
It contains no source code.

**Download:** <https://penmarka.com/download>, which always serves the
latest `Penmarka-Setup.exe` from this repository's
[latest release](https://github.com/kbteck/penmarka-releases/releases/latest).

Each release also includes `Penmarka-Setup.exe.sha256`. To check a
download in PowerShell:

```powershell
Get-FileHash .\Penmarka-Setup.exe -Algorithm SHA256
```

The hash shown must match the one in the `.sha256` file.

Support: support@penmarka.com
