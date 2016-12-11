# Minecraft-BigReactors-Computercraft
Computercraft program for controlling BigReactor reactors and turbines, for use in modded Minecraft

This is still a work in progress.

Instructions:
The program will detect any reactors, turbines, power storage systems and monitors attached to the computer and control them.
It will keep the reactors within the temperature range 800-1200 degrees.
It will keep the turbines between 1820 and 1840 rpm. It will also disengage the coils if the turbine is running under 1700 rpm for faster spin-up.
It will turn the system off if the power stores hit 95% and turn them system on if the power store drops below 5%.

It responds to some key presses:
- 'Q' - Quit
- 'O' - Toggles On/Off, overriding the auto power management
- '1' - Cycles the primary info display through all available monitors, including swapping with the secondary and tertiary information displays
- '2' - Cycles the secondary info display through all available monitors except the one showing the primary info
- '3' - Cycles the tertiary info display through all available monitors except the two with the primary and secondary info

To do:
- Prettify the text output. It is very basic at the moment
- Work out why the time delay vanishes after pressing a key
- Save which displays are showing primary, secondary and tertiary info and restore them on program restart
- Add support for wireless connections.
