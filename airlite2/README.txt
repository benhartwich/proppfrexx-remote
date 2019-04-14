README

IMPORTANT!
Before you start please fully backup your current settings!

Files:
- airlite-config-preset: Load this preset at the airlite configuration manager
- airlite.events: Load this events file at the general settings => Events/Commands
- airlite.mixer: ProppFrexx Mixer and Routing for Airlite (C:\Users\YOUR-USERNAME\AppData\Roaming\radio42\ProppFrexx ONAIR\4.0)
- Default.drl: GPIO Remote Mapping for Airlite (C:\Users\YOUR-USERNAME\AppData\Roaming\radio42\ProppFrexx GPIOClient\4.0)

How is the Airlite configured in this sample?
Channel 1-3: Mic
Channel 4: Player A 
Channel 5: Player B
Channel 6: Cartwall and Modstream and Overlay Player
Channel 7: PFL Player
Channel 8: VoIP / Skype
Both rows of control buttons 1-16: Cartwall 1 (start / stop 1-16 entries)

Local soundcard: Monitor signal (same as PFL).

USB 1 Output (Main Out): In 1 at ProppFrexx. This channel has to selected for stream source. Hasn´t to be unmuted. (see page 19 of the airlite manual)
USB 3 Output (Voice Track signal): In 2 at ProppFrexx for voice tracking and pre recording your voice. (see page 19 of the airlite manual)

Installation:
1) Import all files at the right direction.
2) Check your mixer settings and add the correct usb channels of the airlite to your single in- and outputs.
3) Restart ProppFrexx.

Update:
Because of an incompatibility it is not possible to send back Autoplay On / Off action from ProppFrexx to Airlite. If ProppFrexx turns Autoplay off, you have to manually exit the nonstop mode at Airlite. Only the way Nonstop Mode on / off => Autoplay On / off in ProppFrexx is working.

