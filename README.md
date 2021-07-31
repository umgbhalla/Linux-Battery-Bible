# Linux Battery Bible
The supreme guide for maximizing battery life out of your laptop running Linux!
     
     
Look, we can all agree that most of the time, Windows does give better battery life than Linux. But it doesn't have to be like that :)

# The casual talk
You might've already got this recommended, but I'm just putting it here again.

### Switch browsers!
Try switching to a browser like Brave. While Firefox is an extremely good browser, it is a bit heavy on the battery.

### Decrease brightness!
Ah yes, the good old tip of increasing battery, decreasing the brightness of your display! :)

### Install TLP!
TLP is a tool that can help improve battery life and optimize it, it is pretty configurable and some settings can help increase battery life.    
I usually just use the default configuration that it generates.    
      
Installation - https://linrunner.de/tlp/installation/index.html    
      
### Install powertop and calibrate it!
Powertop is an extensive tool for advanced power usage statistics and it can really help out battery life.    
Powertop is available on most package managers, for eg. on Ubuntu - `sudo apt install powertop` should install powertop.     
          
After installing powertop, run these commands - 
```
sudo powertop --calibrate
sudo powertop --auto-tune
```
Remember that the calibration process might completely turn the display off, do not worry and try to not increase the brightness while it is calibrating. Calibration can take a while.

# The maybe not-so common tips

### Install thermald! (Intel processers only)
thermald is an open source daemon made by Intel and can improve battery life, install it through your package manager. For eg. Ubuntu - `sudo apt install thermald`

### Install CPUFreq!
This tool is extremely useful and I've personally a decent amount of extra battery, `indicator-cpufreq` is the package name and it should be available on most package managers. For eg. Ubuntu - `sudo apt install indicator-cpufreq`

# The *advanced* tips

This is a bit of an advanced area and if you're a beginner, try taking help from a pal while doing this.

### Undervolting.
Undervolting is basically giving the CPU less energy, effectively increasing battery life!
