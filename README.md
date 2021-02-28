# Conky Lua Reloaded

A simple conky configuration based on [Conky Lua](https://www.gnome-look.org/content/show.php/Conky+lua?content=139024).

## Introduction

This nice script was a bit outdated and the syntax was too old. After some tweaking and bug fixing in the code it can still be used in newer versions of **Conky (> 1.10)**.

## Installation

1. Install

 - Debian / Ubuntu derivates:   **apt-get install conky-all**
 - Fedora                       **dnf install -y conky**

2. Clone the repo:              **git clone https://github.com/pablods90/conkyLuaReloaded.git**
3. Copy the files **conkyrc** and **clock_rings.lua** to the config folder **~/.conky**.
4. Run conky and tweak it by editting the configuration file **conky -c ~/.conky/conkyrc**. You can edit it while it is running, it will detect the changes and apply them on the fly.


## Suggested packages

These packages are advised in case you want to have broader monitoring options (such as weather, temperatures, etc):
- lm-sensors
- curl
- hddtemp


## Screenshoots

![alt text](https://raw.githubusercontent.com/pablods90/conkyMonitoring/master/Screenshot%2020170720a.png)
![alt text](https://raw.githubusercontent.com/pablods90/conkyMonitoring/master/Screenshot%2020170720b.png)
