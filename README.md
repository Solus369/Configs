# Configs
My Local Config Files

Alacritty:
          This config features the terminus font family as the deafault font and Iceberg Dark as the color scheme. It also features an opacity value of 0.6. It comes with the underline cursor by default.(Terminus Font (TTF) must be installed for this to work or the font can be changed to one of the available fonts)
          
Htop:
      Just the defaults with CPU Temeperature monitor enabled by default.

Awesome WM:
            This invloves a lot of major changes from the default rc.lua file. The wibar is removed by default, so a new panel can be added according to your choice like polybar or continue without any panel with a minimalistic appearance just like mine. Nitrogen and Picom has been added to the autostart list(In order for this to work both the programs should be installed first).Alacritty is the default terminal which can be changed according to your liking.

Picom(Compton):
                Fade-in and Fade-out between workspaces and windows has been enabled and the amount of fade can also be changed according to your preference. It is best if you set fading = false if you are facing any performance issue. Opacity of the alacritty terminal has been turned on by default and other programs can also be added to that list. Blurring has been turned off due to bad performance which will be fixed by the picom team in their further updates. This config is compatible with other compton forks but it is best to use it with picom or just replicate this in the config file of the compton fork that is being used by you. It will be similar to this and you won't face any issues. 
