# unzipsfx-win32-build

## Overview

This README file describes the setup required to be able to compile unzipsfx-win32 at Windows Server 2016 (or any recent windows version)

## Pre-requisites

To build unzipsfx we need Visual Studio 2017 installed (free community edition installer can be obtained [here](https://aka.ms/vs/15/release/vs_community.exe)

We just need to download the installer, execute it and wait till installation has finished (can take a while)

## Build steps

To build unzipsfx tool under Windows, follow these steps:

* Be sure that pre-requisites are met (you have installed Visual Studio 2017 as described above).
* Clone/Download this repository into your local machine. You will obtain the following workspace:
![unzipsfx workspace](./win32/images/initial_workspace.png)
* Using your windows explorer, go to the folder where you downloaded the codes, and then go to the **win32/VC2017** directory. See screenshot below:
![unzipsfx win32 V2017 folder](./win32/images/win32_VS2017_workspace.png)
* Double click the solution file detailed below (this will launch the Visual Studio IDE).
![unzipsfx win32 V2017 folder](./win32/images/win32_VS2017_workspace.png)
* Once IDE is launched (see screenshot below), select the unzipsfx project, under solution Explorer -> unzipsfx (see screenshot below), press right click and then select compile.
![unzipsfx win32 V2017 folder](./win32/images/win32_VS2017_workspace.png)
* Build process will create a new output folder under win32/VC2017/ . This folder contains the unzipsfx executable.
![unzipsfx win32 V2017 folder](./win32/images/win32_VS2017_workspace.png)
