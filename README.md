# Install-Arch-linux
How to install arch linux on ORACLE Virtual Box:

1. Download the oracle virtual box :) 
https://www.virtualbox.org/

2. Download the arch linux iso image from the offical website for that you can use torrent or whatever you like
In order to download using the torrent simply download the torrent file then use utorrent or either qbtorrent in order to download it.
https://archlinux.org/download/

3. After succesfully downloading the iso image now open the virtual box

4. Click on NEW option then add the iso image in it.

5. Then start the machine, let the machine if everysteps are done correctly you will get a terminal with root privileges now run the following command :

 1. setfont ter-132n
 2. Check for stable connection using: ping archlinux.org
 3. Type `pacman -Sy` to synchronize the packagelist.
 4. Then install the arsenalinex keyring package `pacman -Sy archlinux-keyring 
 5. Launch the archlinux installer script : archinstall(without any spaces)
  if the command is not found install it using packman -Sy archinstall

Then we will navigate through the installtion process using the arrow keys and set which ever values are required by us to set..
In order to set values simply navigate to the option and then click enter..

Note while setting the root password you wont be seeing the password that you have entered so believe in yourself that you are cooking something xD

6. Now add a new user by navigating to profile option..
7. Now most important step so proceed with caution 💀

Navigate to Profile option then select the Desktop option then choose the desired desktop env for this you can simply google and get to know what these environments means..
In order to choose simply navigate to the name and then press TAB then you will see a * sign it means that option have been choosed.

8. Then change the Audio option to Pipewire(for best results)
9. Then change the Network configuration use the Network Manager 
10. Finally select the time zone then cross check all the options make sure nothing is left empty.(ignore the Disk encryption and additional packages option)
Then navigate below and click on install.

And now take a break drink water annd let the process run...\

Then type neofetch command
then type exit
then shutdown now


Then headover to the vm and click on settings then click on storage and click on the CD icon and then click the remove virtual disk option

And you are done now simply start the virtual machine..

