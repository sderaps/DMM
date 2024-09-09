Diabetic Watch Faces Created with Samsung Watch Face Studio that are Compatible with Wear OS 5+ using GlucodataHandler for the Visually Impaired

File DMM1.wfs was created with WatchFaceStudio_1.6.10.exe on Windows 11.  

Thanks to Pachi81 for GlucodataHandler Here: https://github.com/pachi81/GlucoDataHandler

I created a very simple watch face for my MDI Injections with 5 oversized, extra large complications for better viewing experience for the visually impaired for Dexcom G7, xdrip+ companion for the Galaxy watch 7 ,using very specific Complications from glucodata handler app on phone and watch. I'm still learning and the watch face still needs work, but it's functional enough. I will try out the Libre 3 on in in a few weeks too. Anyone wanting to help fix the face is welcome. Installing the watch face on wear os 5 is a bit complicated, and you have to use WatchFaceStudio_1.6.10 program. You Load the file and send it to watch via ADB using the Function "Run on Watch" in the Watchfacestudio App. I will try to find detailed instrucions on how to install the watch face. My hope is that a watch face developer can take this idea to the next level and make the face better and the install process easier. This watch face complications uses very specific glucodataandler customization. Sooo, Warning !! Other customizations will NOT look right and the font will be tiny or ridiculously oversized. Also when touching the watch face, it brings me to alarms and I don't know how to fix that or make it go somewhere else. 
From the top left Complication going accross using Glucodatahandler specific Customizations are as follows. 
1. Glucose and Trend (big and colored),
2. Delta big,
3. IOB
4. Glucose time stamp
5. Samsung Timer 

My Method to install watch face on my Galaxy Watch 7

Step 1. Connect your watch and computer to the same Wi-Fi network 

Step 2. Enable Developer Options on Watch
go to Settings > About device > Software info, then tap the Build number until “Developer options enabled” appears on the screen. 
Go back and select Developer Options at the bottom of /settings

Step 3. Put you watch on a usb charger and open Developer Options
    select “Stay awake when charging”
    select “ADB Debugging”
    select “wireless debugging then check wireless debugging in enabled,

on the next screen, Now ensure wifi address is the same on both computer and watch, scroll down and select Allow. 
It will bring you back to the previous screen. 

Step 4. Now go to Samsung Watch Face Studio on PC load the file DMM1.WFS then select “Run on Device” 
    Click + next to scan devices
    Add your ip address  (example 192.168.1.106)
    Then add port number that is after you ip: (example 34669)
    Then click + on watch to (Pair new device)
    Add Pairing code from watch to pairing code emplt slot in watch face studio.
    Add Pairing Port Number from ip address at the bottom after Example (192.168.1.106:36749) then enter (36749)

Then select ok and the face will apear on your watch in about 14 seconds. Watch will dissconnect after the file is sent. If you 
want to send another file, you will have to pair again. I'm guessing, or there is somekind of build in ADB timeout build into wear os5. 
Good Luck..


Samsungs reference to install "run on Watch. Please note I did not use BT method I used wifi method, seems like Samsung Need to update this page. https://developer.samsung.com/galaxy-watch-tizen/studio/tutorial/connect.html#:~:text=Open%20the%20Run%20on%20Device%20panel%20in%20Galaxy%20Watch%20Studio&text=Then%20select%20the%20watch%20on,it%20to%20Galaxy%20Watch%20Studio.
