# Installation Guide
This page will guide you through the OSBLE+ VS Plugin simple installation process.  The first step is to download the plugin and prerequisite install files on the [downloads](https://osble.codeplex.com/releases) page.

_Note that the plugin version may be different than what is displayed below._

![](Installation Guide_download1.png)

To install the OSBLE+ VS Plugin, you must download and install both the prerequisites file as well as the main VSIX file.  Be sure to download the files appropriate to your version of Visual Studio.  Begin by downloading and installing the prerequisite files:

![](Installation Guide_prereqs1.png)

Having installed the prerequisite files, next download and install the VSIX file appropriate to your version of Visual Studio.

![](Installation Guide_prereqs2.png)

After successfully installing the VSIX, you must now close and reopen all open instances of Visual Studio.  At this point, you may be interested in reading about [Starting the OSBLE+ VS Plugin for the First Time](Starting-the-OSBLE+-VS-Plugin-for-the-First-Time).

## Common Installation Problems
* Visual Studio crashes or gives an error message stating that it cannot connect to the server and the error details mention "Awesomium.Core": 
	* Please ensure that you have installed BOTH the prerequisites as well as the plugin. 
* If the installation of the VSIX was not successful, you may have already installed OSBIDE at which point you need to visit the page on [Uninstalling the OSBLE+ VS Plugin](Uninstalling-the-OSBLE+-VS-Plugin).  
* If clicking on the VSIX installation file does not cause the installer to launch, you may need to right-click on the file and open with the "Visual Studio Version Selector."  
	* If the Visual Studio Version Selector is not an option, you may need to manually browse to the file on your computer.  On 64-bit systems, the location is "C:\Program Files (x86)\Common Files\Microsoft Shared\MSEnv\VSLauncher.exe".  On 32-bit systems, the location is "C:\Program Files\Common Files\microsoft shared\MSEnv\VSLauncher.exe".  