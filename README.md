# SS-On-Linux
A guide to running Succubus Stories natively in linux without the need for a proton or wine layer in between

# Prerequisites 
A working copy of Succubus Stories from one of the following places
  * [steam](https://store.steampowered.com/app/3750980/Succubus_Stories/)
  * [itch (free)](https://outsiderartisan.itch.io/succubus-stories-free)
  * [itch (patron)](https://outsiderartisan.itch.io/succubus-stories-patron)

A basic understanding of Linux command line
and due to the compressed nature of this game a copy of binwalk
| OS     | Command             |
|--------|---------------------|
| Fedora | dnf install binwalk |
| Debian | apt install binwalk |
| arch   | pacman -S binwalk   |

if you feel the need to add another package manager to the list dont be afraid to open up a Pull request

# Installation

1. Get any (windows) version of Hex installed to your system please remember where you install it we will need this folder later
2. Clone a version of SS On Linux and extract it to a place of your choosing
3. Open the config.conf with a file editor of your choice
4. Set the PACKAGE_SOURCE to your SS filepath and save the config (Optional will also get prompted in the installer)
5. Double click the installSSOL.sh and launch it

**If you couldnt launch the installer follow these instructions**
1. open the command line into the SS-On-Linux folder
2. run the command chmod +x installSSOL.sh
3. run the installSSOL.sh either through the commandline or by double pressing it
4. Congrats Succubus Stories should be installed in the startmenu now

# Disclaimer
I am not affiliated with Outsider Artisan this is just a quick project i've made so that when the steam version comes out i can play natively on linux, bugs might occur due to this being an unnoficial port, please dont go around reporting bugs to him without checking if it is a port issue, you can always contact me through github issues if such an issue occurs
