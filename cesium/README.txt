 ██████╗███████╗███████╗██╗██╗   ██╗███╗   ███╗   ███████╗██╗  ██╗███████╗
██╔════╝██╔════╝██╔════╝██║██║   ██║████╗ ████║   ██╔════╝╚██╗██╔╝██╔════╝
██║     █████╗  ███████╗██║██║   ██║██╔████╔██║   █████╗   ╚███╔╝ █████╗  
██║     ██╔══╝  ╚════██║██║██║   ██║██║╚██╔╝██║   ██╔══╝   ██╔██╗ ██╔══╝  
╚██████╗███████╗███████║██║╚██████╔╝██║ ╚═╝ ██║██╗███████╗██╔╝ ██╗███████╗
 ╚═════╝╚══════╝╚══════╝╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝╚══════╝╚═╝  ╚═╝╚══════╝1.1
The You Killed Niko Trojan

=============================================================================================

Hello! This is my first GDI malware ever, named cesium.exe. This malware took about a month to
be made, and was written in C#.

This is the version 1.1 of it. What it added is window distortion payloads (resize, random location),
title text modifications, more programs to run at the end (and now they open faster), and an icon!
(also added inversion effect in the second payload) :)

This malware is very rare, as since it's private.

This malware uses undocumented features such as NtRaiseHardError for triggering a BSoD

In order to run it, install .NET Framework 4.0 (should be in this folder).
Run on Windows XP/7 with Basic theme only because otherwise the gdi would be VERY VERY VERY slow.

=============================================================================================

Credits go to Clutter (CYBER SOLDIER), CiberBoy, MalwareLab150 (Mattia), and holymacaroniwhybruh.
HUGE thanks to CiberBoy for making the first payload, optimizing the error icon payload, and helping me
with window distortion payloads!
Thank you all for the help with my trojan! :D

=============================================================================================

by silverjetes <3
02/25