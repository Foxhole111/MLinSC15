DcscUSB driver

The DcscUSB driver is necessary to connect FPGA based laboratory setups designed 
by DCSC technical staff to a PC. Currently the driver supports the 64 bits versions of
Windows 7, 8.1 and 10 (32 bits should work too but is untested).


Installation for Windows 10:
Note: If driver signature enforcement is already disabled, start with step 10.

A disable driver signature enforcement:
1) Connect a FPGA based setup, the driver installation will silently fail.
2) Open the Start Menu, type "Bitlocker" and start it if present, otherwise continue to step 4.
3) Click on "Back up your recovery key" and save on other device/write down your 48 digit recovery key.
4) Hold shift while selecting restart to open Advcanced startup
5) Click on the Start Menu button and type "recovery options".
6) Click on Troubleshoot.
7) Click on Advanced options.
8) Click on Startup Settings. (You might need to select "more options")
9) Click on Restart.
10) Wait while the PC restarts and then press key 7.
11) Login again and unpack the drivers zip file in a directory.
12) Open the Start Menu, type "device manager" and start it.
13) Right-click on the name of the setup (sometimes just called Unknown device) 
    under "Other devices" and select Update driver software....
14) Choose to Browse for driver software on your computer and point it to the Win10 
    sub-directory in the directory from step 11.
15) Allow the installation of the unsigned driver. If the installation fails because 
    a hash is missing, driver signature enforcment is still/again on. Retry the 
    procedure from step 1. If the installation fails again, seek help.
