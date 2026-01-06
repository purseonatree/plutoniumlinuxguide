# plutonium-linux-guide
Guide on how to get CoD Plutonium working on Linux

# In this GitHub repo I will show you how to get [Plutonium.pw](https://plutonium.pw/) fully working on Linux

### Known Issues (as of right now)
* Black Ops 1 is missing SFX Volume even when its maxed out
   (i tried playing vanilla via steam and everything works fine buit for some reason Pluto T5M has this issue on Linux)
* ~~For some reason Wine's file explorer does not let the user search through folders that start with a "." (i.e, .local) and to fix this you're gonna have to use your file explorer of choice, and copy the directory of your game that's located in the .local folder, THEN you have to paste it in the wine explorer however you have to use the corresponding hard drive letter (like windows, default Linux Filesystem is Z:) and then replace the normal slashes "/" with the back slashes similar to windows "\"~~ [Install ProtonTricks from Flathub](https://github.com/Matoking/protontricks), select "Non-Steam Game Plutonium", then you select "Select the default wineprefix" and finally select "run winecfg." from there select "Drives" and make sure "Show dot files" is checked and then select apply and exit  
  
# Step 1, install the [plutonium launcher](https://plutonium.pw/docs/install/)

# Step 2, install Steam

### Arch:

```sudo pacman -S steam```

### Debian/Ubuntu/POP!_OS/Mint

```sudo apt install steam```

### Fedora/RHEL Deriatives

```sudo dnf install steam```

### Gentoo

[Use this section of the Gentoo Wiki for installing Steam](https://wiki.gentoo.org/wiki/Steam#Emerge_.28recommended.29)

### FOR PEOPLE WHO WANT TO DO FLATPAK/FLATHUB (ANY DISTRO)

```flatpak install steam```


## Once you install Steam you can go ahead and sign in as per usual.


# Step 3, Enable "Steam Play"

Go ahead and click on the Steam icon on the top left corner and click on "Settings" 

Scroll a tiny bit, select "Compatibility" 

and then Select both "Enable Steam Play for supported titles" & "Enable Steam Play for all other titles"

### Go ahead and restart and you should be able to install anything you want using Proton, including Non-Steam Games.

# Step 4, Installing the supported CoD Titles
You need to purchase all of them on Steam in order to play them on plutonium except MW3 (as plutonium has a system that checks game ownership) 
* [CoD: Black Ops 2](https://store.steampowered.com/app/202970/)
* [CoD: Black Ops](https://store.steampowered.com/app/42700/)
* [CoD: World at War](https://store.steampowered.com/app/10090/)

NOTE: THE MW3 GUIDE IS LEGAL BECAUSE THE GAME FILES ARE PROVIDED BY ACTIVISION THEMSELVES
(Directorly from [Plutonium's site](https://plutonium.pw/docs/install/#iw5-modern-warfare-3))
# MW3
## Method 1
Installing it from this Steam link 

* Put this in your browser
```steam://install/42750```

## Method 2

### 1. Go to LIBRARY and from the dropdown menu select TOOLS.

![image](https://github.com/doomjuantoo/plutonium-linux-guide/assets/90519725/2d9610c1-6a66-463c-9555-74754d590fa8)


### 2. Locate Call of Duty: Modern Warfare 3 - Dedicated Server, select it and then click the cog icon then Properties.

![image](https://github.com/doomjuantoo/plutonium-linux-guide/assets/90519725/f5f9c4a6-c807-43bc-9a6e-cf107eb5b813)


### 3. Navigate to the LANGUAGE tab and ensure the language is step to English this is very important as unfortunately the Steam MW3 Dedicated Server can not install all languages and would result in missing files / errors.

![image](https://github.com/doomjuantoo/plutonium-linux-guide/assets/90519725/8f916b1b-a6c2-4893-b7db-308ac5e60c67)

### 4. Select INSTALL then Next then Finish.

![image](https://github.com/doomjuantoo/plutonium-linux-guide/assets/90519725/666758ad-7797-4e29-a20c-2aaa90522b5c)

![image](https://github.com/doomjuantoo/plutonium-linux-guide/assets/90519725/3de8abbc-7d1f-4aaa-b1b7-e8c21d443f25)

