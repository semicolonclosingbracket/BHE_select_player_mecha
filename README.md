  # About the mod
  This project is a mod for the game BALDR HEART EXE, allowing to select other mecha as the player mecha.

  # (1) How to install
  Download the file BHE_select_player_mecha.pac, rename it as "Update[?].pac", where [?] is a number between 2~9, the final filename should be like "Update3.pac" or "Update6.pac".
  After the installation, **enter the config menu and turn off the option of "ネットワークへの接続 (connection to Internet)"**, as the mod cannot be used when there is connection to Internet.

  # (2) Swift the player mecha
  The mod will replace Level 1~3. The map of all the three levels is "Black background", if they are still the original levels, then the installation of the mod was failed.
  Here are the functions of the three levels:
  Level 1 : Swift the player mecha from Sou to the mecha selected as the practicing enemy.
  Level 2 : Load a portion of the resource (such as pictures and sounds) of the current player mecha. When accessing a level, the resource of Sou and the enemies is loaded. If the current player mecha is not included in them, the game will crush. **So Level 2 must be accessed before accessing a level without the current player mecha.** However, if the current player mecha is one of the enemies of the level, there should be no resource from Level 2 has been loaded (or it will disturb the A.I. of the enemy). If there is already, access Level 3 to unload the resource from Level 2.
  Level 3 : Unload a portion of the resource of the current player mecha.
  
  After clicking the "START" button on the startup screen, the player mecha is always set as Sou / Schwertiger (which is always refered as "Sou" in the following text). To swift the player mecha, select the mecha which the player mecha will be swifted to as the practicing enemy. Then access Level 1.
