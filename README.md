# openHAB WLAN-LED-Stripes Light-Effects

If you have openHab and WLAN-LED-Stripes (i.e. Generic Magic UFO-WiFi LED-Controller connected to a LED-Stripe) you can add with these scripts some features to your openHab. These files containing example items and an example sitemap which should enables you to have quick results.
It's needed that the Wifi LED Binding is installed.

## The Features:

### Sunrise (to be used for a wake up i.e.)
* 3 phases
	* Red (the sun will arise soon but can't be seen yet)
	* Fading from Red to Yellow (the sunrise)
	* Fading into White (If you have a RGBW-LED-Stripe the sun will appear completely and the sky will be white )
* set how long each phase should take, between 1 and 60 minutes
* set a maximum level (depending on how sensitive you are early in the morning)

### Phone Alarm
For this feature you need a FritzBox which is dealing with the calls and the "FritzBox" binding installed.
* If somebody is calling all LED-Stripes will blink between red and white that for sure you will notice that someone is calling.

### Evening Light
For this "Astro" binding needs to be installed.
Half an hour before sunset the LED-Stripe will be switched on with a randomized color and will be switched off at 23:30.
* set the saturation and brightness you would like to have

## Planned Features
* BlinkingLight in several colors: Could be used for Phone Alarm, Wake Up Alarm, Disco light, etc.
* FadingLight in several colors: Could be used for romantic moods, party, etc.
* Sunrise: Set the brightness of the 1st phase.
* Sunrise: Final Blue sunrise phase to push the melatonin level ;)
* Sunrise: Optimised fading
* Evening light: Set when the light will be switched off or how long it should stay switched on.
* Sunset
* Phone Alarm: To set colors to the phone alarm - depending on who is calling  
* TV Simulator (to fake that someone is at home)

(Any suggestions? Please let me know!)


## Change Log:

### Version 0.7.1
* Added the "astro" stuff as an example.
* For "Evening Light" the saturation and brightness can be set.
* Added rule "Blinking Brightnes" to be used i.e. for Alarms.
* Fixed, cleaned and translated the example sitemap.

### Version 0.7
* "Evening Light" won't be switched on if the light is already switched on.
* Minor fixes and changes for a more general use.