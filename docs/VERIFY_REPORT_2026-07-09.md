# Verify Report 2026-07-09

## Evidence

- Rebuilt release packages in $newDist.
- Verified zip target entries against expected SHA256 values.
- Re-exported current local installed DLL strings after overwrite to C:\Users\Administrator\AppData\Local\Temp\ff14-plugin-localization\strings\post-overwrite-20260709-152905.
- Process check before local overwrite: Get-Process | ? { $_.ProcessName -match 'ffxiv|XIVLauncher|Dalamud|ff14' } returned no rows.

## Static Verification Result

All rebuilt zip target DLL/resource hashes matched the expected local hotfix artifacts.

## Remaining Runtime Verification

Not yet verified in-game after package rebuild. Check Dalamud load status, plugin windows, and dalamud.log after launching XIVLauncherCN / FFXIV.
