```
# How to install a NVIDIA driver on Ubuntu 16.04
# Download a driver from https://developer.nvidia.com/vulkan-driver
sudo nano /etc/default/grub
# Uncomment GRUB_TERMINAL=console
# Uncomment GRUB_GFXMODE=640x480
sudo update-grub
sudo reboot now
# Press CTRL + ALT + F1
sudo service lightdm stop
# Press CTRL + ALT + F2
# Press CTRL + ALT + F1
chmod +x NVIDIA-Linux-x86_64-460.39.run
sudo ./NVIDIA-Linux-x86_64-460.39.run
# On "Would you like to run the nvidia-xconfig utility..." choose "Yes"
sudo reboot now
```
---
```
QT_DEBUG_PLUGINS=1 ./ngfx-ui
```
