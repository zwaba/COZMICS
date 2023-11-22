# COZMICS
4 asynchronous delay lines / Plugin lv2 build with Max Gen~ for the Mod Dwarf

Parameters:

REC   / record inputs

Mix	 

Time  / select time between 100 and 6000 ms

Double   / activate delay 3 and 4	

Reverse   / reverse delay 1 and 2

Feedback  / 1 = infinite loop

Crossfeed   / delay 1 and delay 2 feed eachother   / and  delay 3 and delay 4 feed eachother   

Speed   / select speed (1/2x , 1x, 2x)  for delay 1 and 2

Disto   / add distortion in the feedback

Filter  / -100 -> 0   LP  ,   0 -> 100  HP

Filter_On     / filter on/off


Mod devices installation:

• Copy the zwabo-cozmics.lv2 folder to your Mod:
```
  scp -rp <path to zwabo-cozmics.lv2> root@192.168.51.1:/root/.lv2
  ```


• Enter password "mod"
• Reboot Mod
