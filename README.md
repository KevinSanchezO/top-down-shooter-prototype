<h2 align="center">Top Down Shooter Prototype</h2>
<br>

<p align="center">
This is a document to give an overview regarding the controls and mechanics that are included in [videogame name yet to be selected]<br>
</p>

<img align="center" src="images-readme/overview-gameplay.png" alt="Health and bullets ui" style="width:75%;"/>

<h2 align="center">Controls</h2>

<p align="center"> Movement        => W,A,S,D </p>
<p align="center"> Shooting        => Left click </p>
<p align="center"> Pick weapon     => Space bar </p>
<p align="center"> Bullet time     => Shift </p>
<p align="center"> Recover health  => Z </p>

<h2 align="center">Mechanics</h2>

<h3 align="center"> Health and bullet time</h3>

<p align="center">
Player health is displayed at the top-left of the screen. Press <b>Z</b> to recover health using the two health<br>
packs indicated on the right side of the health bar. Use them wisely, as they are limited.<br>
<br>
Press <b>Shift</b> to enter bullet time (slow motion), which costs 5 health points. The bullet time gauge,<br>
located below the health bar, will deplete until it reaches zero, exiting bullet time. You can also exit <br>
bullet time by pressing <b>Shift</b> again, but you cannot re-enter until the gauge is full.
</p>

<br>
<img align="center" src="images-readme/health_recovery_bullettime.png" alt="Health and bullets ui"/>
<br>

<h3 align="center">Stress system</h3>

<p>
The stress system increases the player's damage based on the number of enemies killed in a<br>
short time. Prioritize weaker enemies to build up stress and deal more damage to stronger ones. The <br>
stress meter, displayed at the top-right, has 6 bars indicating the current level, with a timer bar below<br>
it. To raise or maintain the stress level, kill enemies before the timer runs out. If the timer reaches <br>
zero without a kill, the stress level resets.<br>
</p>

<br>
<img align="center" src="images-readme/stress_level.png" alt="Stress system ui"/>
<br>

<h3 align="center">Weapon management</h3>

<p>
The player can carry one weapon at a time. Press the <b>Space</b> bar to pick up a new weapon, dropping<br>
the current one. The weapon UI at the bottom-right displays the current weapon and remaining<br>
rounds. Weapons with available rounds shine, while empty ones do not.<br>
</p>

<br>
<img align="center" src="images-readme/weapon_handler.png" alt="weapon handler ui"/>