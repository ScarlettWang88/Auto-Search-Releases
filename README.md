# Auto-Search Releases

This public repository contains signed Auto-Search desktop update packages and the update manifest only.

- macOS: Apple silicon (ARM64) app ZIP
- Windows: x64 portable ZIP
- `update-manifest.json`: Ed25519-signed package metadata used by the app

The Auto-Search source repository is private. No customer files, file names, keyword groups, reports, logs, telemetry, credentials, or source code are published here.

Auto-Search file scanning and preview remain local and offline. Network access is used only when a user manually checks for updates or explicitly enables automatic update checks in Preferences.

Current test builds are protected by the update signature but are not yet signed with Apple Developer ID or Windows Authenticode. macOS Gatekeeper or Windows SmartScreen may therefore show a warning.
