## Realisation
### Download the iso File
Ich habe das iso File, das ich für die Installation von Linux Arch brauche auf einen USB-Stick geladen. Das iso file habe ich auf der offizielle Seite von Linux Arch heruntergeladen.

### Setup der linux Arch Command konsole
Ich habe den USB-stick in meinen Laptop gesteckt und beim Start die F12 Taste gedrückt, damit ich ins bootmenu komme. Im Bootmenue wählte ich den USB-stick aus und gelange schliesslich zur Linux Arch Konsole.
![alt text](Commandprompt.png)

### Installation von Linux Arch
In der Konsole musste ich sehr viele Befehle eingeben. Es war nicht sehr schwierig, weil mir das Tutorial auf Youtube sehr geholfen hat. Zuerst musste ich eine stabile Internetverbindung haben und verwendete das Ethernetkabel. 
Im nächsten Schritt habe ich das Speichermedium eingerichtet und zwei Partitionen erstellt. 
Danach habe ich einige Pakete für Linux Arch installiert. Dafür benutzte ich den befehl: pacman -S (Paketname)
![alt Text](InstallationKernel.png)

Diese paket beinhalten extra Funktionen und sorgen dafür das das system besser funktioniert. 
Ausserdem aktivierte ich Dienste, die beim Start von Linux Arch starten sollen. Dafür benutzte ich den Befehl: systemctl enable (name des Dienstes)

### Installation Bootloader GRUB
Ich brauche einen Bootloader, damit ich Linux Arch auch ohne den USB-stick booten kann. Dafür verwende ich GRUB.
GRUB habe ich auch wieder mit dem Befehl Pacma -S installiert.
Anschliessend habe ich das Betriebssystem neu gestartet und konnten Linux Arch ganz ohne USB-stick starten. Jetzt fehlt nur noch ein schönes Desktop Environment.
![alt Text](GRUB.png)
![alt Text](GRUB2.png)

### Installation der sddm
Ich installierte den Loginscreen der KDE.
![alt Text](sddm.png)
![alt Text](Login.png)

### Installation von Plasma KDE
Dieser Schritt hat nicht ganz funktioniert. beim Download hat es einige Errors gegeben, wo der Host nicht gefunden wurde. Dadurch konnte ich mich beim Loginscreen
nicht anmelden.
![alt Text](Plasma.png)