<h2 align="center">Top Down Shooter Prototype</h2>
<br>

<p align="center">
This is a document to give an overview regarding the controls and mechanics that are included in [videogame name yet to be selected]<br>
</p>

<h2 align="center">Controls</h2>

<p align="center"> Movement        => W,A,S,D </p><br>
<p align="center"> Shooting        => Left click </p><br>
<p align="center"> Pick weapon     => Space bar </p><br>
<p align="center"> Bullet time     => Shift </p><br>
<p align="center"> Recover health  => Z </p><br>

<h2 align="center">Mechanics</h2>

<h3 align="center"> Health and bullet time</h3>

<p align="center">
The player's health is presented at the top-left side of the screen, the player can recover health<br>
pressing <b>Z</b> with the use of health packages represented as two icons on the right side of the player's health.<br>
Thus the player can only recover health twice, use the health packages wisely.<br>
<br>
The player can enter bullet time, slow motion, pressing <b>Shift</b>. When this mode is activated the player's<br>
health is reduced 5 points and during this mode the bullet time gauge on the bottom of the player's health will be <br>
consumed until reaching 0 exiting bullet tim. Bullet time also can be exited pressing <b>Shift</b> again but cannot <br>
enter it again until the gauge is full.
</p>

<br>
<img src="images-readme/health_recovery_bullettime.png" alt="Health and bullets ui"/>
<br>

<h3 align="center">Stress system</h3>

<p>
The stress system is a mechanic in which the more enemies the player kill under a period of time, the higher<br>
the stress level gets and the more damage is dealt to enemies. The goal with this mechanic is for the player to<br>
prioritize weaker enemies in order to built up the stress level to be able to deal more damage to stronger ones<br>
getting rid of them quicker. the stress system is located at the top-right side of the screen with a window with<br>
6 bars representing the current stress level. Under this window there is the timer as a progress bar. The player must<br>
kill an enemy to rise the stress level or maintain it when level 6 is reached. If the player does not kill anything<br>
before the timer reaches 0 the stress level re-starts.
</p>

<br>
<img src="images-readme/stress_level.png" alt="Stress system ui"/>
<br>

<h3 align="center">Weapon management</h3>

<p>
The player can carry one weapon at any time. Weapons can be picked pressing the <b>Space bar</b> droppring the previous weapon.<br>
At the bottom-right side of the screen is the weapon UI in which the current weapon the player is handling will appear with<br>
the current number of rounds. The pickable weapons with rounds left shine but unlike the ones with no rounds left.
</p>

<br>
<img src="images-readme/weapon_handler.png" alt="weapon handler ui"/>