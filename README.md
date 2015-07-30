# Trader-Klen
Files go in dayz_server.PBO, i have one custom building folder i place it in. 
two files: 
1. TraderKlen.sqf
2. Klen_road.sqf //Credits go to SadBoy1981, since its a ripoff of his trader city
Open dayz_server\system\server_monitor.sqf
place end of file under: 	publicVariable "sm_done";
};
//Klen Trader City
execVM  "\z\addons\dayz_server\CustomBuildings\trader_Klen.sqf";
execVM  "\z\addons\dayz_server\CustomBuildings\Klen_road.sqf";
Repack PBO
Done. 

Trader location I use, replace coordinate and directions.: 
Weapon: [11476.782, 11355.366, -0.010404646], Direction: 188.80544;
Ammo: [11475.82, 11359.924], Direction: -86.788223;
Medic: [11480.106, 11296.244, 0.18066138], Direction: -71.526535;
Building supply: [11473.288, 11300.212, 0.18279764], Direction: 27.022564;
Food and stuff:  [11470.935, 11299.071, 2.8624496],  Direction: 13.879483;
Cars [11486.782, 11327.324, 0.055571053], Direction: -65.478203;
Bankier (If you have one): [11466.5,11311,0.111511], Direction: 312;
