# Readings: Startup Sequences and BIOS
## Why this topic matters
#### - This topic matters because knowing about the BIOS and startup sequence will allow us to know more about how a pc operates.
#### - Now that we know about the hardware components within the computer, it is time to learn about the firmware that allows the hardware and software to communicate with each other.
#### - Knowing how the BIOS executes code to check on the status of essential components and loads the information necessary to run the operating system is important to understand in the ops and cybersecurity field.
### What is the BIOS?
#### - The BIOS stands for Basic Input Output System, it provides the programming that enables components such as the CPU to communicate with other hardware. Essentially, BIOS is hundreds of tiny programs that tell the pc everything from what time it is to what kind of computer it is.
### Use analogies from your previous background to explain what happens during the booting process?
#### - During the boot process, the BIOS is trying to get things started in order for people to use the computer to write docs or surf the web.
#### - The thing to understand is that BIOS locates the first bootable devices in its boot device sequence. This is usually the hard drive, USB, or optical drive that contains the operating system (OS). Once the POST process is done successfully, the OS loads its core files, drivers, and services into the Random Access Memory (RAM).
#### - An analogy I would use would be a NASCAR pit crew, the race car pulls up to the pit crew and they get to work checking the tires, refueling, and making sure that the car is good to go. That's what BIOS
### What is the “Power On Self Test”?
#### - The power on self test (POST) is a special program that is initiated when the computer is turned on or reset.
#### - The POST program runs checks on the pc every time it boots. It sends out a command that checks on all essential components on the computer such as keyboard, mouse, drives, and ect.
#### - At the end of a successful POST, the pc produces one or two short beeps. If the POST is not successful you will see error text or rapid beeping.
### What is the CMOS?
#### - The CMOS stands for complementary metal-oxide semiconductor, it's a small battery built into the chipset. The CMOS contains a tiny bit of writable memory. The CMOS setup utility stored in the system ROM enables you to configure important system BIOS settings stored in the CMOS chip such as CPU setup, boot device sequence, and more.  
### What is the CMOS battery?
#### - CMOS battery is the power supply for the BIOS, since the BIOS needs to remain operational even when the pc is not powered on, the CMOS battery is installed on the motherboard to power the BIOS firmware.
### Things I want to know more about
#### - I would like to know more about the BIOS replacement; the UEFI. I understand that UEFI is slowly replacing BIOS as the default firmware for computers and I think it would be to my benefit to learn about how UEFI works compared to BIOS.
