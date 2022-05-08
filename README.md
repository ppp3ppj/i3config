# My i3 config!
Hi! this is my personal setting i3 to use in my computer. 


## Detail<br>
**Distro** : EndeavourOS  
**Display manager** :  Ly  
**Desktop environment** : i3  
**Shell** : zsh  
**Terminal** : xfce4  
**Polybar** : 3 Monitors - settting for PC  
**Other** : dunst, feh, rofi, dmenu, font-manager, nvim, visual studio code  



## Troubleshooting in my pc
| Problem | Fix |
|--|--|
|  Buzzing Sound from Speakers [Intel Chipset] |`sudo nvim /etc/modprobe.d/snd_hda_intel.conf`  Now, **edit** the file and **add** the following line: `options snd_hda_intel power_save=0` **Save** the text file and **reboot your system**. [Detail](https://wiki.archlinux.org/title/Advanced_Linux_Sound_Architecture/Troubleshooting#Pops_when_starting_and_stopping_playback)
||

