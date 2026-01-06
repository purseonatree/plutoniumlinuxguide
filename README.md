# Plutonium Linux Guide (WAW/BO1 Lag & sound fix included!)

Hello! This is a guide for getting the Call of Duty Plutonium client working on Linux with as little issues as possible. This includes fixes for every COD game supported by the Plutonium client. We will try to keep this guide as concise as possible and update this guide as time goes on and Proton improves.

# Quick Notice

This is NOT a piracy guide. We recommend obtaining these games legally if possible. Consult the official Plutonium installation guide (hyperlink to that page here) for better guidance on this, and use your own discretion if you wish to borrow these games from a friend.

This is not in any way shape or form affilated with Plutonium or the Plutonium Team. We just like the client and we love Linux!

# FOR STEAM DECK LCD USERS

Using Windows reportedly works, but Steam Deck LCD users on SteamOS and possibly other distros can ONLY play in LAN mode. Attempting to play normally will result in a banned hardware error. This is due to Plutonium's hardware ID ban protocol eventually flagging a cheater on the Steam Deck, resulting in every user with one being affected since each Deck shipped with the same hardware ID. If you wish to play Plutonium online on a Steam Deck, the OLED version is currently unaffected.

# Required Dependencies

[Steam](https://store.steampowered.com/about/)

[ProtonTricks (Flatpak & Convenience Reasons)](https://flathub.org/en/apps/com.github.Matoking.protontricks)

[Proton GE (Good because of NTSync giving these games significant performance gains)](https://github.com/GloriousEggroll/proton-ge-custom)

## Bit more optional but highly recommended dependencies

[ProtonUp-Qt (Easier to obtain & update GE from)](https://flathub.org/en/apps/net.davidotek.pupgui2)

# The Actual Guide

This was tested on Gentoo, CachyOS (Arch), & Linux Mint (Ubuntu/Debian)

## Step #1

Buy the actual games on Steam if possible. (and ofc install them)

[World At War](https://store.steampowered.com/app/10090/Call_of_Duty_World_at_War/)

[Black Ops 1](https://store.steampowered.com/app/42700/Call_of_Duty_Black_Ops/)

MW3 Server Tool (The Free and legal method): steam://rungameid/42750

[Modern Warfare 3](https://store.steampowered.com/app/115300/Call_of_Duty_Modern_Warfare_3_2011/)

[Black Ops 2](https://store.steampowered.com/app/202970/Call_of_Duty_Black_Ops_II/)

## Step #2

Installing ProtonTricks via Flatpak

### Ensure Flathub's repo is in your flatpak (and make sure [flatpak](https://flathub.org/en/setup) is installed on your system)

`flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo`

### Installing

``flatpak install flathub com.github.Matoking.protontricks``

## Step #3

Install [Plutonium's Launcher](https://cdn.plutonium.pw/updater/plutonium.exe) and keep it in a directory that isn't in your Downloads, like your Documents for now.

## Step #4

Install Proton GE, Technically you can just use Proton Experimental or any stable official release of Proton. However GE has [NTSync](https://docs.kernel.org/userspace-api/ntsync.html)
and has proven to give SIGNIFCANT performance increases for these old COD games. [Here's a good video covering the differences, the key is the frametimes.](https://www.youtube.com/watch?v=lZUxteV40tc)

### For ProtonUp-Qt Users

Just select GE in the GUI, select your Steam directory and hit install.
