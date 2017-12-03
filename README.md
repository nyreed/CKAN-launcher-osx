# CKAN-launcher-osx

This is a MacOS launcher for [CKAN, a mono based Kerbal Space Program Mod Manager](http://forum.kerbalspaceprogram.com/index.php?/topic/154922-ckan)

##CKAN

CKAN is cross platform mod manager for Kerbal Space Program targetting .NET 4.5 / Mono 4.0.

This is just a simple app bundle containing the [CKAN](http://forum.kerbalspaceprogram.com/index.php?/topic/154922-ckan) executable and a startup script to run it in the mono environment. 
This provides a way to run CKAN via GUI.

Updates should be handled by CKAN.exe. On update the app will quit. Just open it again.

##Requirements

The app requires mono 4.0 to be installed. You will be prompted to download it if needed.

All mods and CKAN files are stored in ~/Library/Steam/steamapps/common/Kerbal Space Program, as when running the program from the terminal.

Logs to ~/Library/Logs/CKAN. Check logs there first if the app just bounces in the dock.

## Compatibility

Tested on MacOS El Capitan 10.11.6 with mono 4.6.1 installed from http://www.mono-project.com/download/

Not tested with mono from homebrew/macports/fink.

## Licensing 

The app bundle contains a copy of ckan.exe v.1.22.6, which is MIT licensed.