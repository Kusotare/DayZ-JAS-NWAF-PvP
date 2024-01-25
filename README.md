Place the player spawn gear json file into the "custom" folder.

Backup the original cfgPlayerSpawnPoints.xml, and upload the supplied one.

Add this line to your cfggameplay.json in the "PlayerData" section, see example below:


"PlayerData":
	{
		"disablePersonalLight": [true/false],
		"spawnGearPresetFiles": ["custom/JAS_NWAF_PvP_OG_Loadout.json"],   <-- Add this line
		"StaminaData":


After all files have been edited and uploaded, restart the server for the changes to take effect.
