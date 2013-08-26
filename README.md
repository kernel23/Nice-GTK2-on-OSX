Nice-GTK2-on-OSX
================

Configure default GTK2 fonts to be nicer in OSX (ie: Wireshark).

~ > cat .gtkrc-2.0
gtk-font-name = "Calibri 11"

~ > cat .Xresources 
Xft.dpi:        96
Xft.antialias:  true
Xft.hinting:    true
Xft.lcdfilter:  lcdlegacy
Xft.autohint:   true
Xft.rgba:       rgb
Xft.hintstyle:  hintfull
Xft.renderFont: true

That's all folks.
