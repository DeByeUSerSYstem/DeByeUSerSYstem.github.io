---
layout: page
title: Install or compile Debussy
permalink: /install/
---

---

## How to install Debussy


### Software requirements

- Python ver. \<=3.8 installed on your system. We recommend using [Anaconda] [1]. During the installation of Anaconda, select the option *“Add Anaconda to the User PATH environmental variable”*, although not recommended by the installer.
- [Java] [2]. This is only required for the integrated atomistic models visualization tool.
- *Only MacOSX*: [XQuartz] [3]. Note: restart your computer after the installation.


### Installation on Windows

- Move the `cygwin64` folder in the `C:\` directory. Other location are not supported.
- Run `install_v2.2.bat` as administrator (right click \> Run as administrator). If not possible, run the file normally (double-click).
- If the installer failed to update your `PATH` environmental variables, you can do it yourself by adding `C:\cygwin64\bin`. [Tutorial to add an environmental variable] [4].
- Launch Debussy by double-clicking on `debussy-suite_GUI.bat` in the `C:\cygwin64\DEBUSSY_v2.2` folder.


---



[1]: <https://www.anaconda.com/>
[2]: <https://www.java.com/>
[3]: <www.xquartz.org>
[4]: <https://www.opentechguides.com/how-to/article/windows-10/113/windows-10-set-path.html> "Set PATH and other environment variables in Windows 10"


