Clipboard JSON included
-----------------------
Open each file in /eventSheets, copy ALL text, then in Construct 3 open the matching Event Sheet and Paste.
If your build supports JSON clipboard, the events will be created automatically. If not, the text doubles as a precise spec.

Objects to create (names exact):
- Player (Sprite, Platform, ScrollTo, BoundToLayout) → vars: HP=3, FireCD=0, Weapon="basic", Facing=1, Aim=0, AimLock=0
- Bullet_basic (Sprite, Bullet), Bullet_spread (Sprite, Bullet), Bullet_laser (Sprite, Bullet)
- Enemy (Sprite, Platform; Disable default controls) → vars: HP=3, Dir=1, FireCD=0
- EnemyBullet (Sprite, Bullet)
- Explosion (Sprite; destroy on animation finished)
- Power_Spread, Power_Rapid, Power_Health (Sprites)
- Tilemap (tileset.png), Hazard (collision)
- UI_Health, UI_Lives (Text)

Globals:
- Lives=3, CheckpointX=0, CheckpointY=0