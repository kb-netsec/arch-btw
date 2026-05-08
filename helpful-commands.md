Here's a list of helpful commands for use in Arch systems. Some day I'll get around to organizing it. 

# Package Management
sudo pacman -S <package-name> to install a package

sudo pacman -Ss <package-name> to search repositories

sudo pacman -Qs keyword to search installed packages

sudo pacman -Rs remove package and no-longer needed dependencies

# Put system into low-power state
systemctl suspend

# Update the system
yay -Syu

# Install AUR package
yay -S <package-name>

# Turn PulseAudio volume up/down 
pactl set-sink-volume @DEFAULT_SINK@ -5% / +5$

# Turn screen brightness up/down
brightnessctl set 50%

# Start Docker
sudo systemctl start docker

# Clear SSH hosts file
sudo rm -rf /root/.ssh/known_hosts
