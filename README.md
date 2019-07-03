![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/logo.png) <br />

[Polybar](https://github.com/jaagr/polybar) aims to help users build beautiful and highly customizable status bars for their desktop environment, without the need of having a black belt in shell scripting. <br />

The main purpose of Polybar is to help users create awesome status bars. It has built-in functionality to display information about the most commonly used services. Some of the services included so far... <br />

- Systray icons
- Window title
- Playback controls and status display for MPD using libmpdclient
- ALSA volume controls
- Workspace and desktop panel for bspwm and i3
- Workspace module for EWMH compliant window managers
- Keyboard layout and indicator status
- CPU and memory load indicator
- Battery display
- Network connection details
- Backlight level
- Date and time label
- Time-based shell script execution
- Command output tailing
- User-defined menu tree
- Inter-process messaging
- And [more](https://github.com/jaagr/polybar)... <br />

## // Polybar-4

**How To Use** : Put all files in *'/home/$USER/.config/polybar/'* and execute *'launch.sh'* to start the polybar or add this script to your WM startup file. <br />

***Overview***
- WM : Openbox
- Icon Fonts : [Icomoon-feather](https://icomoon.io/app/#/select/library) <br />
- Text Fonts : [Ubuntu Condensed](https://design.ubuntu.com/font/) <br />

**Color Changer** : In this setup, i created three scripts which are used in changing colors.  <br />

- colors-light.sh &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         // For light themes <br />
- colors-dark.sh &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         // For Dark themes <br />
- color-switch.sh &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        // Module script based on *rofi* <br />

To change colors, there is a module (the feather one) added on polybar which changes the colors in Real-time/In-place or whatever you call it. <br />

***Warning*** : Don't change the script's location, default path is *$HOME/.config/polybar/scripts/*

![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/preview_cm.png) <br />

**Module Tester** : A simple script *tester.sh* also added, which give you a preview of all modules. <br />

![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/preview_tl.png) <br />

***Light Variant***
![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/preview_4.png) <br />

***Dark Variant***
![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/preview_dark_4.png) <br />

**Desktop Preview**
![logo](https://raw.githubusercontent.com/adi1090x/polybar-themes/master/previews/desktop_4.png) <br />
