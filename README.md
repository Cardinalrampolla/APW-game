# APW: No Tea Party!

Consolidated Team B v12.5 development handover for AXEL and Claude.

- `APW_No_Tea_Party_v125_Debug_And_Animation_Polish.html`: complete playable offline game; use this as the consolidated baseline.
- `APW_v125_Debug_And_Animation_Polish_Report.md`: changes, verification and known limitations.
- `APW_v125_Debug_And_Animation_Polish_Transfer.zip`: reproducible source, tests, logs and complete HTML.

The separate Velvet Integration Safety Fixes branch was compared with this build; its fixes are already covered. Do not overwrite this baseline with that narrower build.

Keep the original HTML intact. Future modularisation should build an equivalent HTML and pass the same checks before it becomes the new baseline. Make subsequent changes on branches and review before merging.

Browser progress is separate from the HTML: use the game's JSON backup/import tools to transfer saves.
