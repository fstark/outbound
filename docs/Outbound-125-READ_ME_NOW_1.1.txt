                                         Outbound System Software
                                                     Version 1.1
                                                   Release Notes
                                                  August 3, 1990


_________________________ IMPORTANT! _________________________
  BACK UP YOUR SILICON DRIVE BEFORE INSTALLING VERSION 1.1 SOFTWARE!
____________________________________________________________
Additional information is stored on the Silicon Drive to detect Silicon Drive storage errors as a traditional disk drive does.  You will be REQUIRED to initialize your Silicon Drive the first time you reboot after installing version 1.1 software.  This will completely erase all the data on your Silicon Drive.  This should not be necessary for future updates of the Outbound System Software.
____________________________________________________________
  BACK UP YOUR SILICON DRIVE BEFORE INSTALLING VERSION 1.1 SOFTWARE!
_________________________ IMPORTANT! _________________________


This document describes version 1.1 of the Outbound Laptop System Software, which offers several bug fixes and new features.  We describe solutions to known problems with this release, how to update your Outbound Laptop to software version 1.1, and also recommend a 220 volt to 110 volt power converter for international travelers.


What's On This Disk
________________

We put a Macintosh 6.0.5 System folder on the Outbound System Software disk so you can boot an Outbound Laptop AFTER you install version 1.1.  If you install 6.0.5 BEFORE you install Outbound System 1.1, you will not be able to boot your Outbound.

If you wish to upgrade to Macintosh System 6.0.5, please use a complete set of Apple System Software disks to install it AFTER you install Outbound System Software version 1.1.  The System folder on the Outbound System Software disk has been minimized in order to fit on the disk, so it does not include everything in Apple's System 6.0.5 release.

We included SuperClock! version 3.9 by Steve Christensen, which will display remaining battery time in the menu bar.  Just click on the time shown until a battery icon is displayed.  This is the time remaining on your main battery.

The Outbound SCSI Emulator application on this disk allows you to turn your Outbound into a SCSI device and access its disk drives or silicon drive from any Macintosh attached via the Outbound SCSI Adapter (available now).  Please refer to the SCSI Adapter User Guide for information on using this application.


New Features
___________

• Outbound external floppy drive support: Outbound's External Floppy Drive is now available.  It is SuperDrive™-Compatible, and reads and writes 400K, 800K, and 1.4M Macintosh floppies, and 720K and 1.44M DOS floppies.

• Keyboard reset: simultaneously pressing the “control-option-delete” keys resets the Outbound Laptop.  This has the same effect as pressing the reset button on a Macintosh, so use it as a second to last resort to restart your Outbound (the very last resort is closing the base then restarting).

• System 1.1 displays a dialog box when you attach the keyboard but don’t change to low-power keyboard mode.

• A dialog box warns if you are docked and running from batteries.

• 1.1 now supports the Macintosh 512KE.


Bug Fixes
________

• Macintosh System 6.0.5 fixes several problems known to Apple, including compatibility with Liaison and Apple File Exchange.  Restarts under 6.0.5 no longer crash.

• 400K disks formatted on both sides will now work correctly in an Outbound floppy drive.

• The  Outbound power supply uses a slow trickle-charge method when charging a very low battery.  Outbound System 1.0 would sometimes shut down with a very low battery even when attached to AC.  This is fixed in 1.1: you can now use your Outbound on AC power even when the battery is very low.

• We fixed a disk eject problem that occurred when running the Apple Installer from the Outbound floppy drive.

• We improved 800K floppy performance and reliability.

• We fixed a network timing problem with standalone Outbound SEs on large networks, and adjusted Outbound Plus network timing.


Solutions To Known Problems
________________________

• The Macintosh System accesses RAM in the Outbound faster than RAM in the Macintosh. We recommend that you move as much RAM as possible from the host Macintosh to the Outbound, and maximize the RAM cache on the host Macintosh via the Control Panel. This improves docked performance.   

• If you had difficulty reading a particular floppy disk under Outbound System 1.0, back it up and re-initialize it, then copy the files back onto it after installing Outbound System 1.1. This should improve its readability.

• GCC’s Personal Laser Printer will not work when the Outbound is docked to a Macintosh unless you go to the Control Panel and set the RAM cache to equal the amount of memory you have on the host Macintosh (at least 512K).

• MultiFinder has a bug that can cause a docked Macintosh Plus to crash when you insert a disk in the Macintosh floppy drive after launching an application.  We have reported this bug to Apple.  We can send you a patched version of 6.0.4 or 6.0.5 MultiFinder that fixes the problem if you call Outbound Technical Support at 303.786-9200.

• The Easy Access startup document does not work with the Outbound Laptop System.  It prevents the Macintosh Plus keyboard from working when docked, and can sometimes cause a standalone Outbound SE to rename disks and folders with repeating dashes (“--------”).  Please remove this file from your System folder.

• Shiva Dial-In will crash on a standalone Outbound Laptop with Macintosh Plus ROMs after asking for the network password.  This can be fixed by copying a RAM-based version of the AppleTalk driver file into the System folder on your Outbound.  Outbound System 1.1 is incompatible with version 53 of the RAM-based AppleTalk driver file, so use version 52 or earlier.

• The “CPU Sleep” power-saving feature in the Outbound Control Panel may cause some applications to run more slowly.  Try turning off CPU Sleep if you notice particularly slow performance.


_________________________ IMPORTANT! _________________________
  BACK UP YOUR SILICON DRIVE BEFORE INSTALLING VERSION 1.1 SOFTWARE!
____________________________________________________________


1.1 Update Instructions
___________________

1. Back up your Silicon Drive: you will be required to initialize (erase) your Silicon Drive after installing version 1.1 of the Outbound System Software.  If your start-up drive is your Silicon Drive, you will need to copy your System folder back to your Silicon Drive after installing version 1.1.

2. Attach the Outbound Laptop to the Macintosh and turn on the Macintosh.  Insert the Outbound System Software disk into the Macintosh floppy drive.

3. Drag all the files from the “System Folder Additions” folder on the 1.1 update disk to the System folder on your startup drive.  If your start-up drive is your Silicon Drive, drag the contents of the "System Folder Additions" folder into the backup System folder that you created in step 1.

4. Double-click on the “BatteryDA” icon and use the Font/DA mover to install the latest battery desk accessory into your System file.  

5. Double-click on the Outbound Installer application.  A dialog will be displayed with the current and new version information.  Click on the button to install the correct version for your hardware configuration, then click on the Done button after installation.  

6. If you want your start up drive to be your Silicon Drive, copy the backup System Folder you created in step 1 with the “System Folder Additions” you added in step 3 to your Silicon Drive.  Now Restart the Macintosh (or the Outbound in standalone mode) and enjoy version 1.1 software!


Power Converter And Plug Adapters For International Travelers
__________________________________________________

We tested 50 watt international power converters, and found that the Radio Shack Travel Converter (catalog number 273-1401) and Plug Adapters (catalog number 273-1405) will work under normal 220/240 volt power conditions.  The only problem with the Radio Shack unit is when the power is nominally 220/240 volts, but actually comes out at 200 volts or less.  In this case, the Outbound will not be harmed, but may charge slowly or not at all.  The instructions for the Radio Shack unit advise that it is not designed for continuous use.

NEVER use a power converter larger than 50 watts.  These units are designed for hair dryers, not computers, and will not work with your Outbound.