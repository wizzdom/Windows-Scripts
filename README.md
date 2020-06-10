# Windows Scripts
- Just a bunch of shortcuts and batch scripts that I use almost everyday
- I just needed a way to sync these between my devices and so here it is! ( ͡° ͜ʖ ͡°)

## Some useful commands
### Cipher
- cipher /e {Pathtofoldertoencrypt} (Encrypt empty folder)
- cipher /d {Pathtofoldertoencrypt} (Decrypt folder)
- cipher /e /s:{Pathtofoldertoencrypt} (Encrypt folder with files)
- cipher /w:{DirveLetter} (Wipe empty space on drive)

### ipConfig
- ipconfig
- ipconfig /all (nore detail)
- ipconfig /flushdns (flush DNS)

### Ping/tracert
- ping {ip/hostname}
- tracert {ip/hostname} (Trace Route Basically)

### FC
- fc {fileA} {fileB} (Compare files A and B)

### SFC/DISM (System File Checker/Deployment Image Servicing and Management Tool)
- sfc /scannow (check for corrupted system files and try to repair them)
- dism /online /cleanup-image /restorehealth

### chkdsk
- chkdsk {DriveLetter} /r (Check Disk for eroors and bad sectors and repair them)

### tasklist/taskkill
- tasklist (list running processes)
- taskkill /f /t /im {name of process} (kills process & child processes by name)
- taskkill /f /t /pid {PID of process} (kills process & child processes by PID)

### powercfg
powercfg /energy (generate html report file on system energy efficiency)
powercfg /batteryreport (generate html report file for battery)

### netsh
- netsh wlan show all
- netsh wlan show wlanreport (generate a wlanreport.html file, WiFi connections, WiFi adaptor)
