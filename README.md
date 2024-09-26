# pslicer-configs

Macos config directory: `~/Library/Application\ Support/PrusaSlicer/`

Linux (flatpak) config directory: `~/.var/app/com.prusa3d.PrusaSlicer/config/PrusaSlicer/`  
Linux (snap) config directory: `~/snap/prusa-slicer/current/.config/PrusaSlicer`  
Linux (Appimage) config directory: `~/.config/PrusaSlicer-alpha`  

Windows config directory: `%appdata%\Roaming\PrusaSlicer`

# setup 
open PrusaSlicer once and finish the printer setup to create the config folder
Go to the config directory 

`rm -R filament print printer sla_print`  
`git init`  
`git remote add origin https://github.com/bionik/pslicer-configs.git`  
`git fetch`  
`git pull origin main`  
