# SatisfactoryMod_Speedo
Mod for the Game "Satisfactory" - Speedometer HUD overlay
Page on SMR: https://ficsit.app/mod/6jneNJKyXPsUPX

## Description:
This simple mod adds a few lines of Text overlay to your HUD to display your **movement speed** in a few different ways: In km/h, mi/h m/s, and in Vector form (XYZ + Horizontal speed in m/s).

Additionally, you get a color-changing icon that tells you how fast you are falling/how much it will hurt! Especially helpful for when you're using Hypertube cannons.

Now has some configurability in SML's mod settings.

![IGExample](/auxFiles/example.png "IGExample")

Source is available.
This is my first mod for this game. it's nothing too special, I mostly wanted this functionality myself for a few reasons.

---
### FAQ
- **Q:** Can I change what the overlay displays?
- **A:** Yes, you can! Go to the escape menu, click on 'Mods' and find the Speedo section.
<br><br>
- **Q:** Why no MPH display?
- **A:** You can enable it in the options if you feel it is valuable in a game that uses the metric system everywhere else. It's just disabled by default.
<br><br>
- **Q:** Why is it displaying `0` when I stand on/sit in a Train, etc?
- **A:** The game calculates different kinds of speed. The one that's displayed is relative to the floor you're standing on. It's not meaningful in a vehicle, but there you already get a speed display anyway. I may change this in the future.