	Real Weather
	============

	Author: code34 nicolas_boiteux@yahoo.fr
	Copyright (C) 2015 Nicolas BOITEUX

	Create rain, wind, fog, and sync time on MP game
	Make random weather during the game
	Fast time to play night & day
	
	Usage:
 	1) Turn on "manual" all weather parameters in the mission editor.
	2) add real_weather.sqf in your mission directory and add this line in your init.sqf:
	[] execVM "real_weather.sqf";



	See example mission in directory: real_weather_mission.Altis
	
	Information:
	Jip players are not automatically synchronized, and must wait few time before to be totaly sync.
	There is a very low cpu usage on server / client side 
	
	Licence: 
	You can share, modify, distribute this script but don't remove the licence and the name of the original author

	logs:
		1.3 fix :
			- replace accelerate time by setTimeMultiplier for smooth transition (Krizz)
		1.2 fix :
			- fix time bug
			- add starting weather & date parameter
			- synchronize JIP weather

		1.1 fix:
			- sync MP
			- tune weather rain when cloudy
			- add time parameters

		1.0 original version