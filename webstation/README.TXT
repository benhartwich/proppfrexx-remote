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
Channel 5: Cartwall and Modstream and Overlay Player and PFL (Because Propp can't make PFL on different channels)
Channel 6: Preserved for VOIP. (But can be made to CUE: Processed sound from Stereotool. ON:Another player) 

Both rows of control buttons 1-12: Cartwall 1 (start / stop 1-12 entries)

Soundcards in console are set like this:

Playing: Fader 3 4 5 (Normally USB Codec, USB codec 2, USB codec 3) Rename accordingly.

Recording USB 1 Output (Main Out of console): MAIN at ProppFrexx. This channel has to selected for stream source. Hasn´t to be unmuted.
	  USB 2 Output (AUX/VOIP out of console) VIOPI at Proppfrexx
	  USB 3 Output (Voice Track signal): VT at ProppFrexx for voice tracking and pre recording your voice.
	Check in Proppfrexx mixer where signal comes in .. Rename accordingly.


Installation:
1) Copy all files to the right folder.
2) Check your mixer settings and add the correct usb channels of the Webstation to your single in- and outputs.

Operating:

In Nonstop-mode Fader 3 and 4 should be up. They will turn on automatic.
If nothing is playing you have to start first track manually.

Manual mode: Faderstart is working. Track "unload" when channel set OFF. (Fader all down or button push to turn OFF)

Changing from Manual to Nonstop:
One deck playing, push non-stop button, other fader up. Now running Non-stop.

Changing from Nonstop to Manual:
One deck playing, push other button to turn off, then push Nonstop button. Now in Manual mode.
If you change any other way, player not playing at the time will skip the track loaded. (Unload and load new).
