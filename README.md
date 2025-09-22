# ARK Backups (Nitrado)

## Restore Instructions
1. Stop the server from the Nitrado web interface.
2. Upload all files from `SavedArks/*` to the server directory `arkse/ShooterGame/Saved/SavedArks/` (overwrite existing files).
3. Upload `SaveGames/*` to `arkse/ShooterGame/SaveGames/` (only if you use the corresponding mods).
4. Start the server again.

## Notes
- `Ragnarok.ark` = latest live save.
- `Ragnarok_YYYY.MM.DD_HH.MM.SS.ark.gz` = snapshot backup.
- `.arkprofile / .arktribe` = player and tribe data.
- `.sav` files inside `SaveGames/` = mod-related data (e.g. AwesomeTeleporters, AwesomeSpyGlass).