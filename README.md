# Freezer

Native C# WinForms gaming utility. The current release line is Windows only; Linux and macOS are not supported or shipped yet.

## Downloads

- Windows download page: [freezer-boost-hub.base44.app](https://freezer-boost-hub.base44.app)
- Latest GitHub release: [Releases](https://github.com/wannabe494639-beep/Zayno/releases/latest)
- Stable direct download for the website button: [Freezer-latest.exe](https://github.com/wannabe494639-beep/Zayno/releases/latest/download/Freezer-latest.exe)

Each release includes a standalone Windows executable and a source ZIP.

## Current version: 2.43.0

The Potato Graphics page offers Normal, Light Potato, and Extreme Potato for detected NVIDIA GPUs. AMD and Intel are clearly marked as not yet supported. Fortnite settings are backed up before changes; reset restores the original INI and clears its read-only flag. Extreme Potato can import a user-selected NVIDIA Profile Inspector .nip file. Profile Inspector is not bundled, its driver changes require administrator approval, and Freezer's reset only restores the Fortnite INI.

Push a release/vX.Y.Z branch to build and publish the matching Windows release. The workflow creates the GitHub release tag vX.Y.Z and uploads the stable Freezer-latest.exe asset so the website button can keep a single URL. Linux and macOS releases will be added only after a native port and platform builds are verified.
