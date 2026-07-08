# Verification Report 2026-07-09

- Remote release assets replaced: 9.
- Local enabled plugins checked: 13.
- Bad manifest/DLL/resource checks: 0.
- navmesh/seeds-local.json was missing in local config; created as [] based on upstream behavior returning an empty seed list on load failure.
- Original English help strings patched in Artisan and MacroMate no longer match in the post-patch string extraction.

Runtime status: not yet verified after launching FF14/Dalamud with these exact patched files.
