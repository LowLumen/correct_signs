# Correct signs
For GTA 5 fivem, with this work I tried to correct the road signs that had wrong numbers or street names.
![sign](https://github.com/user-attachments/assets/bfda8072-bf02-4c02-9723-ef0c1c2d33b0)

## Performance
Files and textures are the original ones, the game performance should not change.

I added some extra props to palomino and senora way, you can find them in the "added" folder, in case the game has performance drops you can delete it and keep only the "vanilla" folder.
In any case the added props are from original game and there are not many, you should not notice any differences.

## Installation
Copy the "correct_signs" folder in your fivem resource folder.
Add "start correct_signs" in your server.cfg file


## Info

```bash
--BUGFIX PROPS--

prop_sign_route_15.yft : 
    correct bug texture, original texture has number 13, changed with 15
		
id1_rd_sign1_slod_children.ydd: 1216.53076, -2037.68665, 48.46086
    correct bug lod model
		
fwy_01_fwysign_004.ydr: -393.691681, -1263.454, 36.9842377
    correct bug texture (texture in the edges of the road sign are wrong)
		
fwy_01_fwysign_003.ydr: -438.2314, -1538.55261, 32.22918
    correct bug texture  (texture in the road sign are wrong)


--BUG YMAPS--

ch3_rd1_strm_0: 1612.777, -980.2966, 60.137558
    added prop_sign_interstate_04 (x1)
		deleted prop_sign_road_06g (x1)
		
hei_bh1_rd_strm_5.ymap: -614.4618, -551.8521, 33.5
    changed prop_sign_interstate_02 with prop_sign_interstate_05 (x2)
		
hei_cs2_roads_strm_1: 2869.29932, 3524.9834, 52.7882233
		changed prop_sign_road_06e with prop_sign_road_06g (x3)
		changed prop_sign_interstate_01 with prop_sign_route_13 (x2)

hei_dt1_rd1_strm_4.ymap: 294.567719, -556.5506, 42.1
    changed prop_sign_interstate_02 with prop_sign_interstate_01 (x1) (pillbox)

hei_fwy_04_strm_0.ymap: 1111.29993, 403.3141, 85.0
    changed prop_sign_route_01 with prop_sign_interstate_01 (x3)
	  changed prop_sign_route_01 with prop_sign_route_13 (x2)
		changed prop_sign_route_13 with prop_sign_interstate_01 (x1)		
		added prop_sign_interstate_01 (x3)	
	
hei_hw1_rd_strm_6.ymap: 624.0242, -359.334076, 42.5
    changed prop_sign_interstate_02 with prop_sign_interstate_01 (x2)
	  changed prop_sign_interstate_01 with prop_sign_interstate_02 (x1)
	
lr_sc1_rd_strm_1: -464.8947, -1438.35974, 28.0256062
    changed prop_sign_interstate_04 with prop_sign_interstate_05 (x1)
	

ALL OTHER FILES REPLACE THE WRITINGS ON THE SIGN

	
	
--ADDED YMAP AND PROP--

exit_palomino_stateoffice.ymap: 2425.11255, -180.478561, 92.5  ---   2510.49927, 896.632141, 86.2
    added exit prop sign to palomino state office and senora way
		added road sign service area exit 
		added some speed and curve road signs
  This ymap has lod and lodlight maps



```

## License

[MIT](https://choosealicense.com/licenses/mit/)
