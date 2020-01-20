## Instructions:
- First uninstall current realtek audio driver.
- Restart ur PC with Disable driver signature enforcement: (The procedure below is for Win 10. Win 7 and 8/8.1 has slightly different steps to go into this mode, pls search google/youtube for that)

Go to Settings > Update & Security > Recovery > Advanced startup > click Restart now

Now go to Troubleshoot > Advanced options > Startup Settings > click Restart

After the restart u will get a Startup Settings page, press F7 to go into disable driver signature enforcement.

- Now extract the downloaded driver file "Realtek_HDA_CTAPO_v6.0*****.7z".
- Go to FF00_PG475_CTAPO folder and double click Setup.exe.

Continue with the warning sign and click Install this driver software anyway. Do not restart, select I will restart my computer later.

- Restart ur PC

- Now go to SBConnect2 folder and install "CreativeSBConnect2MasterInstallerOEM.exe", uncheck the launch SBConnect now box at the end of the installation.

- We need to generate a license file for SBConnect2 software, we will do it with the "GenKGA3.1.exe" file which is located in GenKGA folder. Right click on "GenKGA3.1.exe" and select Run as Administrator, click yes in the popup. Now press Win Key+R and type C:\ProgramData\Creative\SoftwareLock and hit enter. Delete all files except CTLNBK2HX2.

(Some antivirus might detect GenKGA3.1.exe as a false posivite as like any other self made exe file, the source of GenKGA file can be found [HERE](https://pastebin.com/BHnvBYWD). Just disable ur antivirus/realtime protection or made the whole setup folder as a safe folder in antivirus.)

- Restart ur PC again. If everything is ok, SBConnect2 will launch automatically after the restart. Play a music file and try different presets in SBConnect app to ensure that creative effects r working properly.

If u have problem with installing the whole process, see the video instructions --> [Part 1](https://streamable.com/agyvf) & [Part 2](https://streamable.com/83o37).                                                                                                         




![alt text](https://i.postimg.cc/QC4wrnkz/Capture.png)


## FAQ:

- Which Windows version is compatible ?

Windows 7 to 10. (For Win 10 I'll probably make a UAD version of the mod)

- Both 32bit and 64bit ?

Yes. This is the only mod I'm supporting for 32bit peasants.

- Which realtek audio chips are supported with this mod ?

Almost every audio chip they made.

- Any plan to add multiple APO in future ?

No, I like things simple and lightweight.

- Any update schedule for driver ?

At least once in every month.
