BOSS GATE + HEALTH BAR
----------------------
1) Place **BossGate** (an invisible collision box) at the entrance to your boss arena.
2) Place **Boss01** and **BossCore** off-screen or in the arena; ensure Boss01.HP = 20 (or match the denominator in the health UI).
3) Add a global variable **BossActive = 0**.
4) Paste events:
   - eventSheets/BossGate.events.json (gate logic)
   - eventSheets/BossHealthUI.events.json (UI logic)
5) On start, Boss is disabled. Crossing **BossGate** enables Boss01 + BossCore and shows the health bar.
6) Health bar auto-sizes each tick as Boss01 loses HP. Hides when Boss01 is destroyed.