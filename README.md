# Conky Lua Reloaded

A simple conky configuration based on [Conky Lua](https://www.gnome-look.org/content/show.php/Conky+lua?content=139024).

## Intro

This nice script was a bit outdated and the syntax was too old. With little twaking and bug fixes in the code it can still be used in newer versions of **Conky (> 1.10)**.


## Installation

1. Install

 - Debian / Ubuntu derivates:   **apt-get install conky-all**
 - Fedora                       **dnf install -y conky**

2. Clone the repo:              **git clone https://github.com/pablods90/conkyLuaReloaded.git**
3. Copy the files **conkyrc** and **clock_rings.lua** to the config folder **~/.conky**.
4. Run conky and tweak it by editting it's configuration file **conky -c ~/.conky/conkyrc**. You can edit it while it is running, it will detect the changes and apply them on the fly.


## Suggested packages

This packages are suggested if you want to have wider monitoring options (suchs as weather, temperatures, etc):
- install
- lm-sensors
- curl
- hddtemp


## Screenshoots

![alt text](https://raw.githubusercontent.com/pablods90/conkyLuaReloaded/master/Background200717.png)
![alt text](https://raw.githubusercontent.com/pablods90/conkyLuaReloaded/master/Screenshot%2020170720.png)


