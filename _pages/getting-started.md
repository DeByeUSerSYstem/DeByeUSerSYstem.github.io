---
layout: page
title: Getting started with Debussy
permalink: /getting-started/
---


## How to install Debussy

### Software requirements

- Python ver. \<=3.8 installed on your system. We recommend using [Anaconda](https://www.anaconda.com/). During the installation of Anaconda, select the option *“Add Anaconda to the User PATH environmental variable”*, although not recommended by the installer.
- [Java](https://www.java.com/). This is only required for the integrated atomistic models visualization tool.
- *Only MacOSX* \- [XQuartz](www.xquartz.org). Note: restart your computer after the installation.

### Installation on Windows

- Move the `cygwin64` folder in the `C:\` directory. Other location are not supported.
- Run `install_v2.2.bat` as administrator (right click \> Run as administrator). If not possible, run the file normally (double-click).
- If the installer failed to update your `PATH` environmental variables, you can do it yourself by adding `C:\cygwin64\bin`. [Tutorial to add an environmental variable](https://www.opentechguides.com/how-to/article/windows-10/113/windows-10-set-path.html).
- Launch Debussy by double-clicking on `debussy-suite_GUI.bat` in the `C:\cygwin64\DEBUSSY_v2.2` folder.


### Installation on MacOSX


- Move into the folder `DEBUSSY_v2.2`
- Run the installer by typing on the terminal: `./install_debussy_v2.2`. You will be asked for root credentials
- Move into the folder `RUN_TEST_UNIX`
- Run the file `drun.sh` and follow the instruction on screen

## Tutorial

