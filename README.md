# SYQEL for OBS

These scripts are used as shortcuts to start OBS in "Extended media streaming" mode which allows OBS to allow mic input usage in browser scource

![alt text](https://i.ibb.co/JCzzwS8/Screenshot-at-Jul-16-23-53-50.png)

## Table of Contents

- [Windowns](#for_windows)
- [MacOS](#for_mac)

## Windows <a name="for_windows"></a>

Copy and paste syqelOBS.bat to the directory  which contains OBS. It usually is located in this path `C:\Program Files\obs-studio\bin\64bit`. If you want to access this file from your desktop, right click on the file -> Create Shortcut -> Desktop

If you want to start OBS with mic input support by using the command line, go to the same directory, open CMP or Powershell and write `./obs64.exe --enable-media-stream`

## MacOS <a name="for_mac"></a>

Download syqelOBS.sh and follow these steps

1. First in terminal make the script executable by typing:

   ```
   chmod a+x (yourscriptname)
   ```
2. Right-click yoursyqelOBS.sh and select "Open with" and then "Other...".
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
