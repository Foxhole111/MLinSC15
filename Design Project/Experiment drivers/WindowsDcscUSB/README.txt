DcscUSB driver

The DcscUSB driver is necessary to connect FPGA based laboratory setups designed 
by DCSC technical staff to a PC. Currently the driver supports the 64 bits versions of
Windows 7, 8.1 and 10 (32 bits should work too but is untested).


Installation for Windows 10:
-----------------------------

Note: If driver signature enforcement is already disabled, start with step 10.
1) Connect a FPGA based setup, the driver installation will silently fail.
2) Click on the Start Menu button and type "recovery options".
3) Click on Recovery options.
4) Click on Restart now under Advcanced startup.
5) Click on Troubleshoot.
6) Click on Advanced options.
7) Click on Startup Settings.
8) Click on Restart.
9) Wait while the PC restarts and then press key 7.
10) Login again and unpack the zip file in a directory.
11) Open the Start Menu, type "device manager" and start it.
12) Right-click on the name of the setup (sometimes just called Unknown device) under 
    Other devices and select Update driver software....
13) Choose Browse for driver software on your computer and point it to the Win10 sub-
    directory in the directory from step 10.
14) Allow the installation of the unsigned driver. If the installation fails because a
    hash is missing, driver signature enforcment is still/again on. Retry the procedure
    from step 1. If the installation fails again, seek help.

 
Installation for Windows 8.1:
-----------------------------

Note: If driver signature enforcement is already disabled, start with step 12.
1) Connect a FPGA based setup, the driver installation will silently fail.
2) Open the charms menu (top right corner) and click on Settings.
3) Click on Change PC settings.
4) Click on Update and recovery.
5) Click on Recovery
6) Click on Restart now under Advanced start-up.
7) Click on Troubleshoot.
8) Click on Advanced options,
9) Click on Start-up Settings
10) Click on Restart
11) Wait while the PC restarts and then press key 7.
12) Login again and unpack the zip file in a directory.
13) Open the charms menu, search for "device manager" and start it.
14) Right-click on the name of the setup (sometimes just called Unknown device) under 
    Other devices and select Update driver software....
15) Choose Browse for driver software on your computer and point it to the Win81 subdirectory
    from in the directory from step 12.
16) Allow the installation of the unsigned driver. If the installation fails because a
    hash is missing, driver signature enforcment is still/again on. Retry the procedure
    from step 1. If the installation fails again, seek help.

 
Installation for Windows 7:
---------------------------

1) Unpack the zip file in a directory.
2) Connect a FPGA based setup, the driver installation will fail.
3) Open the Windows Control Panel, click on System and select the Device Manager. 
4) Right-click on the name of the setup (sometimes just called Unknown device) under 
   Other devices and select Update driver software....
5) Choose Browse for driver software on your computer and point it to the directory from 
    step 1.
6) Allow the installation of the unsigned driver.
