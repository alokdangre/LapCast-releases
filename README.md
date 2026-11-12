# LapCast Releases

Official public downloads for the LapCast Windows agent and Android remote-control app.

## Latest release

[Download LapCast v1.2.0](https://github.com/alokdangre/LapCast-releases/releases/tag/v1.2.0)

- **Windows:** `LapCast-Windows-v1.0.5.zip`
- **Android:** `LapCast-Android-v1.2.0.apk`
- **Integrity:** verify both files with the published `SHA256SUMS.txt`

## Install order

1. Download and extract the Windows agent.
2. Run `Install-LapCast.ps1` from PowerShell.
3. Install the APK on the Android phone.
4. Sign both devices into the same Tailscale network, then pair using the address and code shown by the Windows tray app.

This repository intentionally contains release binaries and release notes only. The application source is maintained separately in a private repository.
