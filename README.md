## Instructions:
- First uninstall current realtek audio driver.
- Restart ur PC with Disable driver signature enforcement: (The procedure below is for Win 10/11. Win 7 and 8/8.1 has slightly different steps to go into this mode, pls search google/youtube for that)

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Download driver "Realtek_HDA_CTAPO_v6.0*****.7z" from here [![Github all releases](https://img.shields.io/github/downloads/shibajee/realtek-hda-creative-sbc-mod/total.svg)](https://github.com/shibajee/realtek-hda-creative-sbc-mod/releases/) and extract it.

- Go to FF00_PG4**_CTAPO folder and double click Setup.exe.

![alt text](/img/warning.png)

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

- Restart ur PC

- Now go to SBConnect2 folder and install "CreativeSBConnect2MasterInstallerOEM.exe", uncheck the launch SBConnect now box at the end of the installation.

- We have to activate the installed software. Go to GenKGA folder and run GenKGA.bat as administrator, activation will be done  automatically.

(Some antivirus might detect GenKGA3.1.exe as a false posivite as like any other self made exe file, the source of GenKGA file can be found [HERE](https://pastebin.com/BHnvBYWD). Just disable ur antivirus/realtime protection or made the whole setup folder as a safe folder in antivirus.)

- Restart ur PC again. If everything is ok, SBConnect2 will launch automatically after the restart. Play a music file and try different presets in SBConnect app to ensure that creative effects r working properly.




![alt text](/img/creative.png)


## FAQ:

- Which Windows version is compatible ?

Windows 7, 8.1, 10/11.

- Both 32bit and 64bit ?

Yes. This is the only mod I'm supporting for 32bit peasants.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

When I have free time.
