# When Magick Meets Brass
This repository includes all you need to play the *When Magick Meets Brass* modpack.

This pack is built on Forge for Minecraft Java version 1.20.1.

## Requirements
### Prism Launcher
This modpack is designed to be imported into Prism Launcher. By using Prism, I will be able to offer you relevant assistance if needed.

Please download the latest version here: https://prismlauncher.org/download/

You may want to write down the location you choose to install Prism Launcher to.

(Prism is the best launcher anyway, especially if you have used MultiMC in the past)

### Java 17
I have encountered issues with Oracle's version of Java 17 while playing this pack, and as such ***strongly*** recommend using Adoptium's Java 17.

Please download the latest "JDK" package of version "17 - LTS" here: https://adoptium.net/temurin/releases/?os=windows&package=jdk&version=17/

(If you use Oracle's Java 17 and encounter a JVM crash, swapping to Adoptium is what solved that for me)

### GitHub Desktop
This repository is designed to be cloned for easy installation with Prism Launcher. To do so, you will need GitHub Desktop (or some other form of Git).

Please download the latest version here: https://desktop.github.com/download/

Note: There will also be releases of the pack that come as a .zip file, which can be manually imported into Prism Launcher.  If you choose to install via zip files, version updates will require more effort on your behalf.

## Installation
### GitHub Desktop (Recommended)
Once GitHub Desktop is downloaded and installed, it will open on the "Welcome to GitHub Desktop" page.

1. Sign in to your GitHub account, or click "Create your free account" if you do not have one. You will then be brought to the "Let's Get Started" page.
2. Click the "Clone a Repository from the Internet" button.
3. Click the "URL" tab, and enter the following in the first field: https://github.com/Sgarr17/wmmb-instance/
4. Find the location of the `instances` folder for Prism Launcher. The default location for Windows is `C:\Users\[name]\AppData\Roaming\PrismLauncher\instances`
5. Enter the location of that folder in the second field.
6. Click the "Clone" button.
7. The _When Magick Meets Brass_ instance should now appear when you launch Prism Launcher. If it does not appear, try creating a blank instance to make Prism refresh the instance list.

### Manual Installation via Prism Launcher
1. Download the latest version of the modpack from the Releases tab on the main page.
2. Open Prism Launcher.
3. Click the "Add Instance" button in the top-left corner.
4. Click "Import from Zip" from the list on the left.
5. Click the "Browse" button on the right.
6. Select the .zip file you downloaded and click "Open".
7. Click the "OK" button at the bottom. The _When Magick Meets Brass_ instance will appear once it is installed.

### Checking Java Version
At time of writing (14/10/24), the version of Java this guide has you install (17.0.12+7) will be automatically selected by Prism Launcher if you installed Java to the default location. 
8. Click on the WMMB instance in Prism Launcher.
9. Click the "Edit" button from the list on the right.
10. In the window that opens, click the "Settings" button from the list on the left.
11. In the section titled "Java installation", verify that the field includes `/Eclipse Adoptium/jdk-17.0.12.7-hotspot/bin/javaw.exe`.
12. If it does not include that file, click the "Auto-detect..." button below the field, select the version that does include the above, and click "OK".

## Java Configuration
### About Java Configuration
_When Magick Meets Brass_ provides a set of Java configurations that Prism Launcher will use to launch the game. WMMB's configuration allocates a minimum *and* maximum of 6 GB (6144 MB) of RAM (memory), and uses Aikar's Flags as the 'Java Arguments'.

Aikar's Flags are a set of tailored 'Java Arguments' that improve upon how Java handles storing things in memory and dumping them when they are not needed. By using Aikar's Flags for Minecraft, you will find that the game has less stutters caused by "garbage collection", which unloads things from memory.

You can read up on what Aikar's Flags do here: https://docs.papermc.io/paper/aikars-flags or obtain them for yourself here: https://flags.sh/

(Note: Prism Launcher does not accept the following arguments from Aikar's Flags: `java` `-Xms6144M` `-Xmx6144M` `-jar` `server.jar` `--nogui`. Prism Launcher has a dedicated section for memory allocation above the Java Arguments section.

### Adjusting Java Configuration
You may need to adjust your memory allocation if:
- Your computer has less than 8 GB (8192 MB) of RAM (memory)
- Your computer runs very slow when the game is open.

To adjust your memory allocation:
1. Return to the page you visited during "Checking Java Version" (select WMMB > Edit > Settings).
2. Find the section titled "Memory".
3. Change the values from "6144 MB" to a lower value (i.e. "4096 MB" for 4 GB).

I have not been able to verify the minimum memory allocation, nor the minimum system RAM required to comfortably run the modpack. Please let me know of any findings related to memory requirements.

_When Magick Meets Brass_ should not have more than 8 GB (8192 MB) of memory allocated.

## Updating the Modpack
WIP

## FAQ
WIP
