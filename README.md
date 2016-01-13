# shellpomo

This is a BASH script to implement a simple [Pomodoro Technique](http://pomodorotechnique.com/) timer. It uses [Zenity](https://help.gnome.org/users/zenity/3.18/) for the user interface and has sound and visual notifications ( using notify-send )

The repository contains:

### shellpomo

The BASH script which does the work.

The following two lines will need to be modified to suit your installation:

    SOUND="/usr/share/sounds/ubuntu/stereo/message.ogg"
    ICON="/home/john/projects/shellpomo/Tomato-icon.png"

*( Future updates will try and make the sound less Ubuntu centric. )*

### shellpomo.desktop

Drag and drop this file to the Unity launcher to add a quick launch icon. Note that you will need to modify the command and icon paths ( right click in File Manager and select "Properties")

### Tomato-icon.png

An icon which is used for the Unity lancher and the notifications.

Tomato icon obtained from: http://www.iconarchive.com/show/paradise-fruits-icons-by-artbees/Tomato-icon.html

Licence for the icon:  CC Attribution-Noncommercial-No Derivate 4.0, http://creativecommons.org/licenses/by-nc-nd/4.0/legalcode

### To Do

1. Add an interrupt/ pause feature for both work and rest periods
1. Make the sound and visual notifications a bit more configurable
1. Remember the user settings from run to run
1. Make the sound a little less Ubuntu centric
