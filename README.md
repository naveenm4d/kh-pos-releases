# Kulatissa Hardware — till releases

Builds of the Kulatissa Hardware cashier app. Releases are published here automatically and the
tills update themselves from them (Settings → Check for updates). Each release has:

- `manifest.json` — the version, notes, and the signature the app checks before installing
- `kulatissa-hardware-windows-amd64.exe` — the app itself (what tills download to update)
- `kulatissa-hardware-setup-<version>.exe` — installer for setting up a new till

Nothing here is installed unless it is signed with the shop's release key.
