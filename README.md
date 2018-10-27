# openHAB WLAN-LED-Stripes Light-Effects

If you have openHab and WLAN-LED-Stripes (i.e. Magic UFO-WiFi LED-Controller connected to a LED-Stripe) you can add with these scripts some features to your openHab.
It's needed that the Wifi LED Binding is installed.

## The Features:

### Sunrise (to be used for a wake up i.e.)
* 3 phases
	* Red (the sun will arise soon but can't be seen yet)
	* Red to Yellow (the sunrise)
	* White (If you have a RGBW-LED-Stripe the sun will appear completely and the sky will be white )
* set how long each phase should take, between 1 and 60 minutes
* set a maximum level (depending on how sensitive you are early in the morning)

### Phone Alarm
For this feature you need a FritzBox which is dealing with the calls and the "FritzBox" binding installed.
* If somebody is calling the LED-Stripes will blink between red and white that for sure you will notice that someone is calling.

### Evening Light
For this "Astro" binding needs to be installed.
Half an hour before sunset the LED-Stripe will be switched on with a randomized color and will be switched off at 23:00.

## Planned Features
* Phone Alarm: To set colors to the phone alarm - depending on who is calling  
* BlinkingLight in several colors: Could be used for Phone Alarm, Wake Up Alarm, Disco light, etc.
* Sunrise: Final Blue sunrise phase to push the melatonin level ;)
* Evening light: Set when the light will be switched off or how long it should stay switched on.
* Sunset

(Any suggestions? Please let me know!)


## Change Log:

### Version 0.7
2018-10-23	"Evening Light" won't be switched on if the light is already switched on.
2018-10-23	Minor fixes and changes for a more general use
