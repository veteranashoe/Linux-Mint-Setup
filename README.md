Linux Mint Setup

> remove Bloat
> update the repository
> add custom repository
> configure /etc/fstab {for NTFS automount}
> download themes, icons, cursors
> configure grub
> upgrade necessary packages
> update software sources {package mirrors}
> configure conky
> install and configure Ulauncher
> configure applets
> configure extension
> copy app config files
> set custom sounds
> set custom ICONS

------------------------------------------------------------
=> Bloat
sudo apt remove simple-scan xreader-dbg bulky hexchat hypnotix rhythmbox transmission-gtk thunderbird redshift-gtk warpinator xreader xviewer

=> Optional Bloat
sudo apt remove timeshift celluloid gnome-calculator imagemagick kdeconnect imagemagick-6-common

=> to install
sudo apt install grub-customizer conky-all deepin-picker alacarte stacer qbittorrent deepin-image-viewer deepin-calculator okular geeqie gwenview mpv vlc soundkonverter thunar bomi fsearch git python3-pip

=> Optional install
nautilus eog kwrite GIMP(flatpak) Blanket(flatpak)

-------------------------------------------------------------
=> Repository
sudo add-apt-repository ppa:nemonein/bomi
sudo add-apt-repository ppa:christian-boxdoerfer/fsearch-daily

---------------------------------------------------------------
=> sudo nano /etc/fstab
/dev/sda3	/media/natalie/Oiacis	ntfs-3g	uid=1000,gid=1000,umask=0022,fmask=0022	0	0

-----------------------------------------------------------
=> Personalization
   #THEME
   #ICONS
   #Cursor ICONS
   #Grub THEME

----------------------------------------------------------------

