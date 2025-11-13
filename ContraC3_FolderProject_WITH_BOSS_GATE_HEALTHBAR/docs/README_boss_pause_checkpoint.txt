BOSS01, PAUSE/INVENTORY, CHECKPOINT
-----------------------------------
Boss setup
- Objects: Boss01 (boss01_body.png), BossCore (boss01_core.png pinned to center), BossBullet (boss01_bullet.png with Bullet behavior).
- Paste events from eventSheets/Boss01.events.json into a 'Boss01' event sheet or merge with EnemyAI.
- Place Boss01 + BossCore in Level01; start off-screen if you want a gate trigger.

Pause/Inventory
- Place PauseOverlay (pause_overlay.png) and InventoryPanel (inventory_panel.png) on the UI layer.
- Paste eventSheets/PauseUI.events.json into a 'PauseUI' sheet.
- P/Esc toggles pause; I toggles inventory; O cycles weapons when inventory is open.

Checkpoint flag
- Place CheckpointFlag (checkpoint_flag.png) in your level.
- Paste eventSheets/Checkpoint.events.json into 'World' or a separate 'Checkpoint' sheet.