# CS2-Demo
This demo.cfg file helps in the process of watching CS2's demo.

# Installation
1. Open the archive and extract its content into the following path folder :

        "...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\"

2. Launch the game, start the replay of a demo ("playdemo [filename]") and type in the console the following command: "exec demo.cfg".

3. Your console should display a message and a sound will be played in-game; otherwise you must have a path issue and the file did not load correctly.

# Usage
- This config rebinds multiples keys, so make sure you restart your game after using it to restore your bindings.
  
- hudon (F5) will display every elements of your HUD.
- hudoff (F6) will remove every elements of your HUD.
- bulletsdecals (F7) will toggle bullet's hitmarkers.
  
- demo_togglepause (KP_0) will toggle between pause/resume.
- reset_timescale (KP_1 / MOUSE3) will reset the speed of the demo; it also reset the value of slowdemo/fastdemo/rewinder/forward/jumptick to its lowest value.
- slowdemosw (KP_2) will slow the timescale; There is 3 different scales you can switch by repeating the command.
- fastdemosw (KP_3) will fasten the timescale; There is 5 differents scales you can switch by repeating the command.
- jtswitch (KP_4) changes the amount of tick for rewinder and forwarder; There is 6 differents scales you can switch by repeating the command (3s/11s/23s/45s/1min/1round).
- rewinder (KP_5 / MOUSE4) will rewind the demo for a certain amount of tick.
- forwarder (KP_6 / MOUSE5) will forward the demo for a certain amount of tick.
- radio (KP_7) will toggle the Auto-Director.
- xraytog (KP_8) will toggle XRAY HUD.
- spec_mode 6 (KP_9) will change the spectate mode.
  
- +slowmo (KP_ENTER) will slow the timescale on keyhold.
- +fastmo (KP_PLUS) will fasten the timescale on keyhold.
- demoui (KP_MULTIPLY) will toggle the demoui interface.
  
- The top keyboard numbers will switch between players.
