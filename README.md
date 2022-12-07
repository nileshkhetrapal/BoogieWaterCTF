# BoogieWaterCTF
A fun capture the flag activity created for a final project for a class by three awesome dudes
A beginner friendly Virtual Machine escape capture flag activity.

To get started download the VM from here:

[BoogieWaterCTF.7z - Google Drive](https://drive.google.com/file/d/1-GYjWE-nLS9Jb4WGqmacXCUbyk0Nypqn/view?usp=sharing)

This lab basically has an ubuntu desktop environment with virtualbox being used to emulate another server. This is an example of nested emulation. You will have to make sure that your attacker box can ping the Vboxwebserver before starting the lab. The virtualbox right now is configured to let the server act as its own entity in whichever network the Desktop VM is connected to. While they'll both take the dhcp address you might have to manually enter the default gateway.

Login to the bigvm with 2616

Start virtualbox and start the server

Login to osboxes with Ch@mpl@1n!22

Check the status of apache2 to make sure it is running

Try pinging your attacker machine

If it doesn't work then don't worry. You might have to manually configure the default gateway.

It should work after that.

If you can access the apache landing page then you are at the starting point of the CTF.

The flag is a file called loot in the Desktop.
