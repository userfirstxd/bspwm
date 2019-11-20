# bspwm
configs default

sudo xbps-install vim xorg-minimal xorg-fonts bspwm sxhkd alacritty feh lxappearance lxdm firefox

mkdir .config && cd .config && mkdir bspwm sxhkd

cp -r /usr/share/doc/bspwm/examples/bspwmrc ~/.config/bspwm

cp -r /usr/share/doc/bspwm/examples/sxhkdrc ~/.config/sxhkd
