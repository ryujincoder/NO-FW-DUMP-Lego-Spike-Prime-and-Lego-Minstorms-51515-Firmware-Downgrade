# NO-FW-DUMP-Lego-Spike-Prime-lego Mindstorms-51515-Firmware-Downgrade
Works with Linux Mac and Windows.


(LUNIX AND MAC USERS you will need to install windows 10 via virtual box unless you have a windows conmuter!
Learn how to do it here:https://www.youtube.com/watch?v=OVwzcfD0wWY )

Once you are running windows we will have to install these softwares.


Lego Spike Prime App (even Mindstorms users this is needed). :https://education.lego.com/en-us/downloads/spike-prime/software  And download the windows 10 version and make sure to DOWNLOAD THE INSTALLER and DONT PRESS "Get The App"


7-zip (WINRAR WONT WORK):https://www.7-zip.org/download.html


Minstorms And Spike's Hub FW: This is the FRIMWARE.ZIP file I released here 

Lastly the 7zip extension :https://www.tc4shell.com/en/7zip/asar/ Scroll down to find the download button

BEFORE WE START YOU MUST HAVE SOME AMOUNT OF KNOW WHAT DIRECTORIES LOOK LIKE AND WHAT THEY ARE. YOU CAN BRICK YOUR DEVICE BUT IT IS VERY VERY NOT LIKELY UNLESS YOU DO STUPID THINGS THAT YOU KNOW ARE DOING WRONG. I AM NOT RESPONSIBLE FOR A BRICKED DEVICE IF THAT HAPPENS.

First open up the Windows disk drive in file explorer then go to; \Program Files\SPIKE\Resouces\ Then right click on the app.asar file and select copy, then paste the app.asar file to your desktop.

Then open the windows disk drive once more and enter the following directiory: \Program Files\7z\ Then there make a Subfoler called "Formats" then enter thet new folder and paste the 32.dll or 64.dll file (depending on the version of 7zip you have) Into the new folder.


Then Move the app.asar file from your desktop to your documents folder in file explorer.


Open 7zip and then open the documents folder then the app.asar file we dragged there. 7z should open the file if not try this. Open the windows disk drive once more and enter the following directiory: \Program Files\7z\Formats\ And replace the 64.dll file with 32.dll file or the 64.dllfile to the 32.dll then reopen the dircetory agin in 7zip.


After you open the app.asar file in 7zip enter the following directory: /app/renderer/flipper-hub /firmware/ That .bin file with a bunch of numbers in front of it is the Hubs firmware MINIMIZE THE 7ZIP WINDOW. Open the firmware.zip in file explorer If you want to downgrade the spikes firmware open the SPIKE folder and if Mindstorms open the Mindstorms folder. Reopen The 7zip windows go back to file explorer and REPLACE the desired .bin file form the Firmware.zip file into 7zip.

You can now exit out of 7zip then open the windows disk drive again then follow this directory for the last time: \Program Files\SPIKE\Resouces\ then replace the app.asar file with the one on your desktop, then close out of file explorer.


Open The lego spike prime app and connect your hub (for vbox users find out how to use usb on virtual box) then after you connect your hub you should see a message that says "Your Hub Os Needs To Be Updated" Press update now and Volla you have succecfully downgraded you hubs firmware.











