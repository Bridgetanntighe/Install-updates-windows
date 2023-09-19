<h1>Linux | Installing, Updating and Removing Software </h1>


<h2>Description</h2>
<br>
There are three learning objectives for this lab: <br>
<br>
Update- The machine I used came preinstalled with an old version of the VLC Media Player. I updated VLC to the newest version. <br>
<br>
Install- l installed the Mozilla Firefox web browser. There was no version of Firefox on the machine beforehand. <br>
<br>
Uninstall - I uninstall the GIMP photo-editing tool from the machine, removing it entirely. <br>
<br />


<h2>Verifying installed software </h2>

1. Checked if Firefox is installed using the command ```dpkg-s```. This showed Firefox is not installed on the system. <br>
2. Checked if GIMP is installed. <br>
3. Ran ```dpkg -s vlc``` showed that vlc is installed but the version is out of date. <br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/358e809c-d1b2-421f-b705-73f080ae0824" height="50%" width="50%" alt="Installing"/><br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/f33d71a8-ca1f-48e2-9171-cacdeb538d35" height="50%" width="50%" alt="Installing"/><br>


<h2>Updating VLC Media Player:</h2>

VLC media player is already installed on the computer, but the version that's installed is out-of-date. I fixed that by updating it to the newest version. <br>
1.```sudo apt-get install -f``` kicks off the update process. It printed lots of text and asked if I would like to continue.<br>
2. When the process was finsihed I typed ```dpkg -s vlc``` to verify the installation. <br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/6557a443-b6ac-49de-9def-0825a1b99160" height="50%" width="50%" alt="Installing"/><br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/1a7b9f8f-7052-41a8-9ba3-b926c3d6ce8e" height="50%" width="50%" alt="Installing"/><br>

<h2>Installing Mozilla Firefox:</h2>

1.  ```sudo apt-get update``` command started the repository update process. <br>
2. ```sudo apt-get install firefox-esr``` <br>
3. ```dpkg -s firefox-esr``` to vertify it's installed.<br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/e1a59bc4-22b5-4bb1-96c4-348e0cfd7f88" height="40%" width="40%" alt="Installing"/> <br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/2e090108-69ca-4bee-a1be-8b000777f91e" height="40%" width="40%" alt="Installing"/> <br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/04cdd046-6cbe-4b26-b9f0-372a9df936bd" height="40%" width="40%" alt="Installing"/> <br>




<h2>Unistalling GIMP:</h2>

GIMP, like Firefox, can be installed and uninstalled using the ```apt-get``` commands that I used to install Firefox. To uninstall GIMP, a similar command is used.
1. ```sudo apt-get remove gimp``` this command will kick off the process of unistalling GIMP.<br>
2. ```dpkg -s gimp``` confirms GIMP was removed successfully.<br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/e136b651-0bb3-4797-a6dc-35c0ba74df01" height="40%" width="40%" alt="Installing"/> <br>
<img src="https://github.com/Bridgetanntighe/Install-updates-windows/assets/134883216/03201930-7fcd-4a6c-82d1-a909f4de727a" height="40%" width="40%" alt="Installing"/> <br>




