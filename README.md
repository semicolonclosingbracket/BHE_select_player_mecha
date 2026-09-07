  # About the mod
  This project is a mod for the game BALDR HEART EXE, allowing to select other mecha as the player mecha.

  # (1) How to install
  Download the file BHE_select_player_mecha.pac, rename it as "Update[?].pac", where [?] is a number between 2~9, the final filename should be like "Update3.pac" or "Update6.pac".
  
  After the installation, **enter the config menu and turn off the option of "ネットワークへの接続 (connection to Internet)"**, as the mod cannot be used when there is connection to Internet.

  # (2) Swift the player mecha
  The mod will replace Stage 1~3, The map of all the three stages is "Black background". If they are still the original stages, then the installation of the mod was failed.
  
  Here are the functions of the three levels:
  
  Stage 1 : Swift the player mecha from Sou to the mecha selected as the practising enemy.
  
  Stage 2 : Load a portion of the resource (such as pictures and sounds) of the current player mecha. When accessing a stage, the resource of Sou and the enemies is loaded. If the current player mecha is not included in them, the game will crush. **So Stage 2 must be accessed before accessing a stage without the current player mecha.** However, if the current player mecha is one of the enemies of the stage, there should be no resource from Stage 2 has been loaded (or it will disturb the A.I. of the enemy). If there is already, access Stage 3 to unload the resource from Stage 2.
  
  Stage 3 : Unload a portion of the resource of the current player mecha. Note: if there is no resource from Stage 2 has been loaded, accessing Stage 3 will crush the game.
  
  After clicking the "START" button on the startup screen, the player mecha is always set as Sou / Schwertiger (which is always refered as "Sou" in the following text). To swift the player mecha, select the mecha which the player mecha will be swifted to as the practising enemy. Then access Stage 1, return to the Practice menu, the player mecha should has been swifted. Before changing the weapon config, **please choose a different weapon set first**, because when the Practice / Equipment menu is just accessed, the shown weapon set is the last weapon set of Sou, and it should not be adjusted when the current player mecha is not Sou.

  After preparing the weapon config, enter the stage selecting menu. If the current player mecha is one of the enemies of the stage to play, just access the stage; If it is not, access Stage 2, return to the stage selecting menu, then access the stage to play.

  # (3) Playing the Replay records
  Since the player mecha is always Sou in the unmodded game, when playing the Replay records, the game assumes the player mecha is Sou and only load the resource of Sou and the enemies. To play a Replay record made with non-Sou player mecha, the player mecha must already be swifted to the one when the replay was made, and access Stage 2 to load its resource if it is required.

  # (4) Reset the temporiary modification from this mod
  When returning to the title or quiting the game, the player mecha is reset to Sou and the resource from Stage 2 is cleaned, but the weapon config and Replay records of other mecha are saved.
