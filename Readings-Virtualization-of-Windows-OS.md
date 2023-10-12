# Readings: Virtualization of Windows OS
# Why does this topic matter?
This topic matters because knowing what an ISO image is used for and how to mount it is a valuable tool for admin and cybersecurity personnel. 
In the future, knowing how ISO’s are burned or created for USB sticks will help us understand concepts such as secure backups and restores.
Also, from a cybersecurity perspective, this allows us to know certain attack vectors for machines and servers. If someone creates an ISO with malware that is installed on a company device, it could cause issues on the network or even a breach in security. 
# What is an ISO File?
- An ISO file, often called an ISO image, is a single file that's a perfect representation of an entire CD, DVD, or BD.
- The entire contents of a disc can be precisely duplicated in a single ISO file.
- The .ISO file extension used by ISO images. Often used to distribute large programs over the internet.
# How do you write an ISO file to a CD, DVD, or removable media (like a thumb drive)?
- There are a variety of ways to make use of an ISO file. The common way back in the day was to burn it into a CD, DVD, BD disc.
    - You put a blank disc in the disc drive, then right click the ISO file and choose burn disc image.
    - Then you pick the correct burner from the disc burner drop-down menu.
    - Lastly, select burn. then the disc ejects from the drive and now you got an ISO CD.
- This day in age, burning an ISO file to a USB device is more common.
    - You download and open the Rufus tool. Then insert a USB drive and select a device. You can select Disk or ISO image. Locate and select ISO image to burn.
    - Under Image option, choose standard windows installation, and then click start.
    - Wait for the status to say "Ready", then close Rufus and remove the USB drive.
# How do you create an ISO file?
- There are several programs that allow you to create ISO files from a disc or a collection of files you have chosen.
    - Create an ISO from a DVD, BD, or CD disc.
        1. Download BurnAware because Windows does not have the capability.
        2. Then run the program and select copy to ISO from the disc images column.
        3. Choose the optical disc drive you plan on using from the drop-down at the top of the window.
        4. Select browse and navigate to the location you want to write the ISO image file to and give a file name.
        5. Choose save and insert into the optical drive you chose (i.e. CD, DVD, or BD).
        6. Select copy and then wait while the ISO image is created from your disc.
# How do you mount an ISO file?
- Mounting an ISO file is usually simple. You would use something called a "disc emulator".
- One favorite free program for mounting ISO images is WinCDEmu because of how easy it is to use.
- To mount just tap and hold or right click the ISO file and choose Mount. The OS will create a virtual drive for you automatically.
# Things I want to know more about.
- I would like to know how individuals can mount ISOs remotely in a corporate enterprise. Additionally, for security purposes, how would one check an ISO file for any miscellaneous code or programs that would compromise the device the ISO could be used on.
