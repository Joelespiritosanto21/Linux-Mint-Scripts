# Linux Mint Scripts
Add and Remove the pre-installed software from Linux Mint with the click of a button

![](<Screenshot/Screenshot1.png>)

## How do I use it?
There are two options: Release and Git. Please choose one.

### Git method
1. From a Terminal, clone this project and cd into it: 
    1. `git clone https://github.com/TheLinuxITGuy/Linux-Mint-Scripts.git && cd Linux-Mint-Scripts`
    2. Type: `chmod u+x ./*.*`
    3. Type: `./Main.py`
4. Select the Application you would like to Install/Remove
5. Click Run

### Release method
1. Download the latest .tar.gz release into your ~/Downloads folder
2. Open a Terminal
    1. Type: `cd ~/Downloads`
    2. Type: `tar -xzf Linux-Mint-Scripts-1.x.tar.gz && cd Linux-Mint-Scripts-1.x` Replace the x with the version you downloaded
    3. Type: `chmod u+x ./*.*`
    4. Type: `./Main.py`
3. Select the Applications you would like to Install/Remove
4. Click Run

## Video
[![Video](https://img.youtube.com/vi/PJytFBO3seM/maxresdefault.jpg)](https://youtu.be/PJytFBO3seM)

## What does each script do?
- **Main.py:** GUI that allows you to Install/Remove applications all at once
-  **AfterInstall.sh:** Runs ALL the scripts **Use Main.py instead**
-  **install-bravebrowser.sh:** Adds the Brave repo's GPG key, Adds the Brave repo, Updates the package list, Downloads and Installs Brave
-  **install-chromebrowser.sh:** Updates the package list, Downloads the .deb package to your ~/Downloads folder, Installs Chrome along with any missing dependencies
-  **install-code:** Updates the package list, Adds Flahub report if needed, Downloads and Installs Visual Studio Code
-  **install-discord:** Updates the package list, Adds Flahub report if needed, Downloads and Installs Discord
-  **install-edge:** Updates the package list, Adds Flahub report if needed, Downloads and Installs Microsoft Edge
-  **install-gimp:** Updates the package list, Adds Flahub report if needed, Downloads and Installs GIMP
-  **install-lutris.sh:** Updates the package list, Adds Flathub repo if needed, Downloads and Installs Lutris
-  **install-steam&protonupqt.sh:** Updates the package list, Downloads and Installs Steam along with any missing dependencies, Downloads and Installs ProtonUp-Qt
-  **remove-firefox.sh:** Removes Firefox
-  **remove-libreoffice.sh:** Removes Libre Office
-  **remove-thunderbird.sh:** Removes Thunderbird Mail
-  etc, etc...
