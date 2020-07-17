# OBS Desktop Shortcuts for Extended Media Streams mode

[![Watch the video](https://img.youtube.com/vi/NkFBOypMCnE/maxresdefault.jpg)](https://youtu.be/NkFBOypMCnE)

These scripts are used as shortcuts to start OBS in "Extended media streaming" mode which allows OBS to enable and allow mic audio input for a browser source

![alt text](https://i.ibb.co/JCzzwS8/Screenshot-at-Jul-16-23-53-50.png)

## Table of Contents

- [Windows](#for_windows)
- [MacOS](#for_mac)

## Windows <a name="for_windows"></a>

Download and paste the syqelOBS.bat file into the directory which contains OBS source files. It usually is located in this path `C:\Program Files\obs-studio\bin\64bit`. 
Then right click on the syqelOBS.bat file while in the source directory -> Create Shortcut -> Desktop

From now on - when you click on the desktop shortcut you've just created you will launch OBS in "Extended Media Streaming" Mode

Alternatively - If you want to start OBS with mic input support by using the command line, go to the same directory, open CMP or Powershell and write `./obs64.exe --enable-media-stream`

## MacOS <a name="for_mac"></a>

Download syqelOBS.sh and follow these steps

1. First in terminal make the script executable by typing:

   ```
   chmod a+x (yourscriptname)
   ```
2. Right-click the syqelOBS.sh file and select "Open with" and then "Other...".
3. Here you select the application you want the file to execute
   into, in this case it would be Terminal. To be able to select terminal
   you need to switch from "Recommended Applications" to "All
   Applications". (The Terminal.app application can be found in the
   Utilities folder)
4. NOTE that unless you don't want to associate all files with this
   extension to be run in terminal you should not have "Always Open With"
   checked.
5. After clicking OK you should be able to execute you script by simply double-clicking it.

If you want to just run OBS in extended media streaming mode using terminal write this on terminal

```
/Applications/OBS.app/Contents/MacOS/OBS --enable-media-stream
```
