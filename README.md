# Kicad Addons
 my preferred Addons for Kicad. These currently include:
 - [weirdgyn/viastitching](https://github.com/weirdgyn/viastitching)

# How to install
To install all plugins at the same time, navigate to the kicad folder in ypour terminal. 

On Windows this is usually ``C:\Users\<username>\Documents\KiCad\<version>``

then execute the following commands to integrate the plugins into the correct folders:
```
git init
git remote add origin https://github.com/Aliquis007/kicad_addons.git
git fetch origin
git checkout -f -B main origin/main
git reset --hard origin/main
git pull origin main --force
``` 

