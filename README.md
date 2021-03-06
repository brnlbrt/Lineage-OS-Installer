# Lineage-OS-Installer
A (currently) unofficial installer for LineageOS written in Visual Basic.

NOTE: The embdedded browsers have been replaced by a better solution called Awesomium. Please download it at "http://www.awesomium.com/download." This will allow us to render web pages correctly, as it is based on Chromium.

A prebuilt version (ready to install, the "normal user" version) can be found at the XDA forum post for this application, although the application is still young, so use it only for tesitng purposes. Regardless, we recommend building off of the source so you have the most up-to-date version.

This is the source for the UNOFFICIAL Lineage OS Installer for Windows. At the time of creating this program, Lineage OS is not prebuilt and ready for download, so when I tested it, I simply subsituted Lineage OS for CyanogenMod. It was tested on my Nexus 7 2013 WiFi (flo), and worked just fine. I do not know if it will work for non-nexus devices, but I am certain it will not work with Samsung devices, as the installation script does not utilize Download Mode. If enough people like the idea of this installer, I (or perhaps someone in the community) will give support to Samsung devices. If people begin to contribute, we can change the author name in the script and graphical program (this) from "PJBeans" to "LineageOS Community"

The developers of this application and the LineageOS Community is not responsible for anyone who bricks their devices. This tool is still in development, and has only been tested on a Nexus 7 2013 WiFi (flo).

# How can I contribute?
Whether or not you are a developer, you can contribute to this application! Check out [CONTRIBUTING](CONTRIBUTING)

# What is here:

- Embedded web browsers for downloading TWRP, GApps, and LineageOS
- Images to illustrate where to find Developer Options, USB Debugging, and OEM Unlocking
- The prebuilt program includes a setup script that copies all needed files.

# What is not here:
- Support for Samsung Devices
- Possibly support for other devices (If Fastboot mode acts differently for some reason on other devices; I am not sure)
- A help (support) page
- A functioning embedded installation script (timeouts do not work correctly, and ping ends the script for some reason.)

# Goals
To make this application as user friendly as possible, we should:
- Create a help page
- Fix the embedded Installation Script
- Make it as fool-proof as we can. The user should feel comfortable with the application, and should not fear to unplug their device.
- Materialize the UI (almost done)
- Make the insallation script more automatized. It currently pauses many times, and requires some user input on their device.
- ^ (It would be quite hard to remove all user input, but let's try to minimize it as much as we can)
- (Feel free to add more goals!)

# FAQ:

This program is an unofficial almost-automatic install for Lineage OS, designed for beginers or users who just would like to install Lineage OS and be done; for users who don't care how to install a ROM, who just want it on their phone.

[-] What does this program do?

This program on its own does not do much; in fact, all it does it give 2 embedded web browsers to download Lineage OS and TWRP. However, it gives a step-by-step explanition on what do, where to save the files, and what to name them. Lineage OS is acually installed through multiple scripts included in this repository.

[-] Why would I want to use this?

Well, you probably don't. This installer was made for folks who would like to install Lineage OS on there phone or tablet, but are to scared to, and just would like to have it on their phone or tablet, and be done. *If you want to learn how to install ROMS, already know how to install ROMS, or are a developer, this program is not for you.

[-] What does the Installation Script do?

The Installation script, normally located at `C:\Tools\LineageOSInstaller\scripts\`, is what acually installes LineageOS onto the device. It gives the user instructions of what needs to be done, and automatically unlocks the bootloader, flashes recovery, and pushes LineageOS.zip to the user (not all at the same time, of course). There are other scripts, however, I did not feel the need to upload them; setup.bat simply sets up the C:\Tools\ directory for the program, adb_check is simply `adb_devices`, and starup.bat simply creates the folder LinOS-Files. I am willing to upload any of these files upon request.

# A few things to mention:

I made this program because I know installing a ROM can come across as difficult for someone who never did it before. Now, I only know some Visual Basic, but not all (which is why the program is so simple). I apologize if some files are missing in this Git Repository, I acually never uploaded to GitHub before. So basically, I know how to install ROMS, however, am not a very skilled developer (although I am learning), so I ask that if I did forget something in this repository that you do not yell in all caps at me. Thank you for understanding.
