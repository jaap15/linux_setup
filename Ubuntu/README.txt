Setup for Ubuntu 18.04

Install tweaks
1. sudo apt install gnome-shell-extensions
2. sudo apt install gnome-tweak-tool

Install Dash-to-Dock from ( https://micheleg.github.io/dash-to-dock/download.html ) 

Install Adapta GTK Theme (In case the top doesn't work)
1. `sudo add-apt-repository ppa:tista/adapta
sudo apt-get install adapta-backgrounds
sudo apt-get install adapta-gtk-theme`

Link to repo: https://github.com/adapta-project/adapta-gtk-theme

2. Set in Appearance
    1. Applications -> Adapta-Nokto-Eta
    2. Cursor -> DMZ-Black
    3. Icons -> Paper (look on how to install paper icons)
    4. Shell -> Adapta-Nokto-Eta
    5. Background/Image -> tealized.jpg
    6. Lock Screen/Image -> tealized.jpg

3. Install Paper Icon Theme ( https://github.com/snwh/paper-icon-theme )
   if you get an error: autoreconf: not found.
   Do a `sudo apt-get install autoconf`

After installing dash to dock if locked screen is showing the icons/taskbar do the following:
1. `sudo mv /usr/share/gnome-shell/extensions/ubuntu-dock@ubuntu.com ~/`
2. Reboot

Link: https://github.com/micheleg/dash-to-dock/issues/649

Change login Screen Background
http://ubuntuhandbook.org/index.php/2017/10/change-login-screen-background-ubuntu-17-10/

Extensions Enabled
-------------------
0.Alternatetab
1.Dash to dock
2.Application menu (Also in Tweaks go to Top Bar and enable Activities Overview Hot Corner)
3.Places status indicator
4.User themes

Close tweaks and reopen

TODO
https://github.com/bhilburn/powerlevel9k
