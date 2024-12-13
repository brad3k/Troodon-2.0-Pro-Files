# Troodon-2.0-Pro-Files
For my Troodon 2.0 Pro printer and any additional files I find handy.

First off, download a copy of Visual Studio Code. It is one of the best "free" code editors out there. It works very well on Klipper. 

When I purchased the Troodon 2.0 Pro, I noticed a very negative review that was somewhat surprising, given that this printer is focused on those who have experience with 3d Printers.

The main issue was related to the printer.cfg file.  So... I "fixed" it.  I started with the config file that was sent, tossed almost all of it out, except for the pin locations and then added a whole series of comments throughout the file.

I comment almost EVERYTHING. That way, when time passes and I have no clue what does what, I can figure it out relatively quickly. If you find it handy, then awesome!

I eventually will move the macros under the macro.cfg file.  I have a few there now, but that's a work-in-progress.

Feel free to use this as you see fit.  I only ask to have my attribution brad3k, left in the file somewhere.
You will need to update two areas to your own printer: the MCU part of the printer.cfg, as it references my serial number to the MCU on my printer. And the input shaper MCU under the s2dw.cfg serial number.  If you don't do that, then you will have several errors pop up right away.

I like KAMP which adds a level of functionality that really makes life easier.  To install, see YouTube or other sources

Enjoy your exploration of the Troodon 2.0 Pro by FormBot