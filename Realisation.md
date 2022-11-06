## Realisation
### Download the installation file
I downloaded the installation file I need for the installation of Linux Arch on a USB-stick. I downloaded the installation file from the official site of Linux Arch and it took only a few seconds.

### Setup of the linux Arch Command console
I put the USB stick in my laptop and pressed F12 on startup to get into the bootmenu. In the bootmenu I selected the USB-stick and finally got to the linux Arch console where I was able to type in commands that are important for the installation.

![alt Text](Command prompt.PNG)

### Installing Linux Arch
In the console I had to enter a lot of commands. It was not very difficult because the tutorial on Youtube helped me a lot. First I had to have a stable network connection to download packages for Linux Arch. I used an ethernet cable. 
In the next step, I set up the storage device and created two partitions. One for main usage and another one where the Linux operating system is stored on.
After that I installed some packages for Linux Arch. To do this I used the command: pacman -S (package name).

![alt Text](InstallationKernel.PNG)

These packages contain extra functions and make the system work better. 
I also enabled services that start when Linux Arch boots. For this I used the command: systemctl enable (name of the service).

### Installation Bootloader GRUB
I needed a bootloader, so I can boot Linux Arch without the USB-stick. For this I used GRUB.
I installed GRUB again with the command: Pacman -S.
Afterwards I restarted the operating system and was a little bit nervous because if it would not have worked I had to redo every single stsep.
I was happy that I was able to boot Linux Arch without the USB-stick. Now only a nice looking desktop environment is missing.

![alt Text](GRUB.png)

![alt Text](GRUB2.png)

### Installing the sddm
I installed the login screen of the desktop environment.

![alt Text](sddm.png)

![alt Text](Login.png)

### Installing Plasma KDE
This step didn't quite work. during the download there were some errors where the host wasn't found. Because of this I could not login to the
login screen and didn't got further into the desktop environment of Linux Arch.

![alt Text](Plasma.png)

### The problem 
I luckily only got one problem in my project. But unfortunately it was a problem I could not solve. While downloading to Plasma KDE I got many errors that the host is not found. This has also to do with the missing namingservice and the DNS. I tryed many ways and typed in many commands that could possibly solve the problem.
I searched hours on the internet and in forums but I could not solve the problem. I find it very strange that there was no problem in the Youtube tutorial.
Because of this problem I don't have a nice desktop user interface. However, the most important functionalities are not limited.
