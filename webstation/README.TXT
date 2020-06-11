IMPORTANT!
Before you start please fully backup your current settings!

Files:
- webstation-events: Load this events file at the general settings => Events/Commands IMPORT
- webstation-mixer: ProppFrexx Mixer and Routing for Webstation (C:\Users\YOUR-USERNAME\AppData\Roaming\radio42\ProppFrexx ONAIR\4.0)
- Default.drl: GPIO Remote Mapping for Webstation (C:\Users\YOUR-USERNAME\AppData\Roaming\radio42\ProppFrexx GPIOClient\4.0)

How is the Webstation configured in this sample?
Channel 1-2: Mic
Channel 3: Player A 
Channel 4: Player B
Channel 5: Cartwall and Modstream and Overlay Player 
Channel 6: PFL to hear Processed sound

Both rows of control buttons 1-12: Cartwall 1 (start / stop 1-12 entries)

Soundcards in console are set like this:

Playing: Fader 3 4 5 (Normally USB Codec, USB codec 2, USB codec 3) Rename accordingly.

Recording USB 1 Output (Main Out of console): MAIN at ProppFrexx. This channel has to selected for stream source. Hasn´t to be unmuted.
	  USB 2 Output (AUX/VOIP out of console) AUX at Proppfrexx
	  USB 3 Output (Voice Track signal): VT at ProppFrexx for voice tracking and pre recording your voice.
	Check in Proppfrexx mixer where signal comes in .. Rename accordingly.


Installation:
1) Import all files at the right direction.
2) Check your mixer settings and add the correct usb channels of the Webstation to your single in- and outputs.

These files were created from Kjeld - thanks!