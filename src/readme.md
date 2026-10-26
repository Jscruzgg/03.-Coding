The installed app checks GitHub Releases for a new version every time it opens. 
If there is one, it updates before 
the app window opens, like Discord: a small "Updating" notice shows while 
it downloads, the new version installs silently over the current one (same folder, shortcuts and taskbar pin, no setup wizard, no questions) and then opens. 
Offline, or if anything fails, the current version opens and it retries on the next launch. 
The portable version does not update itself. The log is at %APPDATA%\ByTune\updater.log (%APPDATA%\Music Desktop\updater.log for copies installed before the app was renamed: they keep their data folder).