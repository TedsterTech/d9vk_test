AudioSurf 2

Tested on build from CattaRappa from 4th April 2019

Launch options used (if any):
From cmd.exe:
Audiosurf2.exe -force-d3d9 -steam -w 1920 -h 1080 -windowed -noborder +mat_disable_d3d9ex 1 +mat_d3d9ex_disabled 1 -dxlevel 90 +mat_dxlevel 90

Symptoms:
Can't get into level, dialog box comes up but can't read it; text rendering broken

Remarks:
To get dx9 working at all I needed to set up with the [before_videosurf] beta.
See log
