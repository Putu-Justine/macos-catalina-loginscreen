# What's this?
This is my own take on making a login screen inspired from OSX Catalina. Based on my dotfiles.
# Status of this rice
- DE Switcher : ✅
- Time & Date : ✅
- Shutdown button : ✅
- Restart button : ✅
- Sleep button : ❎
- Customizable : ❎

# Screenshots
| Location | Screenshots |
| --- | --- |
| **Login Screen/Lockscreen** | ![lightdm](https://github.com/Putu-Justine/macos-catalina-loginscreen/blob/master/.github-assets/screenshots/loginscreen.png) |

# Installation ([How to install LightDM WebKit2 Greeter on Arch Linux](https://wiki.archlinux.org/title/LightDM#Greeter))
Clone the theme and copy to the desired folders
```
git clone https://github.com/Putu-Justine/macos-catalina-loginscreen.git
cd macos-catalina-loginscreen
sudo cp -r lightdm-themes/* /usr/share/lightdm-webkit/themes
```
Now, open /etc/lightdm/lightdm-webkit2-greeter.conf and edit this line
```
webkit_theme = macos-catalina
```
And you are done!
# Special thanks
- [dimaglushkov](https://github.com/dimaglushkov) For the lightdm webkit themes as a base.
- Apple for the wallpapers.