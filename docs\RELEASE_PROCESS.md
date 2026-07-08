# Release Process

1. Close FF14, XIVLauncher, and Dalamud.
2. Patch or add localization resources in the installed plugin version directory.
3. Package each plugin version directory as `<InternalName>-<Version>-zh.zip`.
4. Compute SHA256 for every zip.
5. Upload packages to a GitHub release.
6. Regenerate `pluginmaster.json` with the release asset download URLs.
7. Keep translation maps under `maps/` when the package was produced by string replacement.

Do not blindly translate IPC names, command identifiers, code snippets, file paths, shader names, signature scan bytes, or structured dump field names.
