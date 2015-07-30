# Trader-Klen
Files go in dayz_server.PBO, i have one custom building folder i place it in. <br />
two files: <br />
1. TraderKlen.sqf<br />
2. Klen_road.sqf //Credits go to SadBoy1981, since its a ripoff of his trader city<br />
Open dayz_server\system\server_monitor.sqf <br />
place end of file under: 	publicVariable "sm_done"; <br />
}; <br />
//Klen Trader City <br />
execVM  "\z\addons\dayz_server\CustomBuildings\trader_Klen.sqf";   <br />
execVM  "\z\addons\dayz_server\CustomBuildings\Klen_road.sqf";     <br />
Repack PBO <br />
Done. <br />

Trader location I use, replace coordinate and directions.: <br />
Weapon: [11476.782, 11355.366, -0.010404646] Direction: 188.80544<br />
Ammo: [11475.82, 11359.924] Direction: -86.788223<br />
Medic: [11480.106, 11296.244, 0.18066138] Direction: -71.526535<br />
Building supply: [11473.288, 11300.212, 0.18279764] Direction: 27.022564<br />
Food and stuff:  [11470.935, 11299.071 2.8624496],  Direction: 13.879483<br />
Cars [11486.782, 11327.324, 0.055571053] Direction: -65.478203<br />
Bankier (If you have one): [11466.5,11311,0.111511] Direction: 312<br />
