## Welcome to Diabetic Masked Man!

Diabetic Oversized Watch Face For MDI Injection Created with Samsung Watch Face Studio that are Compatible with Wear OS 5+ using GlucodataHandler for the Visually Impaired.


## Watch Faces for Dexcom G7, Xdrip+, using GlucodataHandler Complications

[DMM1_DexcomG7_Xdrip.wfs](https://github.com/sderaps/DMM/blob/a99a45b547c678e245dffda8d8a1cd8d0372e177/DMM1_DexcomG7_Xdrip.wfs)

![DMM1](https://raw.githubusercontent.com/sderaps/DMM/main/DMM1%20Galaxy%20Watch%20%207%2044mm.jpg)

[DMM2_DexcomG7_Xdrip.wfs](https://github.com/sderaps/DMM/blob/a99a45b547c678e245dffda8d8a1cd8d0372e177/DMM2_DexcomG7_Xdrip.wfs)

![DMM2](https://raw.githubusercontent.com/sderaps/DMM/main/DMM2_Dexcom_G7_Xdrip.jpg)




## Program Needed for Watch Face Installation

**Download Samsung Watch Face Studio** 
(WatchFaceStudio_1.7.9.exe or Higher ONLY): https://developer.samsung.com/watch-face-studio/download.html



## Warning!

These watch face complications uses very specific glucodatahandler customization. Other customizations will "NOT" look right and the font will be tiny or oversized.  You have my permission to download, alter and use the *.wfs file to fit your personal needs. 

*These Watch Faces Were created specifically because of Googles Wear OS Changes on Wear OS 5, making Watch Face Apps Currently Like Pujie Watch Faces no longer Compatible. 

**Older Versions of Wear os Watches, might not work right with the faces posted here. The only way to tell is to test it.

** For older versions of wear os watches, You might be able to find a good watch face and simple tutorial on my Youtube channel: Diabetic Masked Man , link in "about me" at the bottom of this Page 

## Summary
Oversized watch face for MDI Injections with extra large complications for better viewing experience for the visually impaired for Dexcom G7, Xdrip+ for the (Galaxy watch 7 or Pixel Watch 3 Tested), using very specific Complications from GlucodataHandler app on phone and watch. Installing the watch face on wear os 5 is a bit complicated, and you have to use WatchFaceStudio_1.7.9.exe or Higher program. You Load the file and send it to watch via ADB using the Function "Run on Watch" in the Watchfacestudio App. Detailed install instructions below.

**GlucodataHandler Android App** 
Google Play Go Here:
https://play.google.com/store/apps/details?id=de.michelinside.glucodatahandler&hl=en_US

**Xdrip+ Android App ** 
Stable Build Here
https://xdrip.readthedocs.io/en/latest/install/download/
Nightly Build Here:
https://github.com/NightscoutFoundation/xDrip/releases

My Plan is to create and test watch faces for the Liibre 3 in the very soon.. 

## About Watch Faces

**DMM1** Watch Face From the top left Complication going across using Glucodatahandler specific Customizations are as follows.

1. Glucose and Trend (big and colored),
2. Delta big,
3. IOB
4. Glucose time stamp
5. Samsung or Google Timer

**DMM2** Watch Face From the top left Complication going across using Glucodatahandler specific Customizations are as follows.

1. Glucose and Trend (big and colored),
2. Delta big,
3. IOB
4. Samsung or Google Timer
5. Glucose time stamp
6. Watch Battery Level



## Installation

Samsung Watch Face Studio Gave me allot of problems connecting to my watches during the install "Run On Device", I had to spend quite allot of time trying to install the watch face over and over again. But I think I figured it out. Make sure Bluetooth is turned off on the Watch and temporarily disable all firewalls on PC. Then try pairing it again and run on watch. Don't forget to re-enable your firewalls after the watch face installs. At some point when I get this watch face better, I'm hoping I can upload it to google play Store to ease the install process for people. But it's out of my league right now..

Step 1. Connect your watch and computer to the same Wi-Fi network

Step 2. On your Watch Go to Settings/Connections and Turn off Bluetooth.

Step 3. Turn off your PC Firewalls, there are 2 switches for firewalls to turn off in Windows Security on Windows 11. 


Step 4. Enable Developer Options on Watch go to Settings > About device > Software info, then tap the Build number until “Developer options enabled” appears on the screen. Swipe the screen "left to right" to Go back and select Developer Options at the bottom of /settings

Step 5. Put your watch on a usb charger and open Developer Options select “Stay awake when charging” select “ADB Debugging” select “wireless debugging then check wireless debugging in enabled,
 
  on the next screen, Now ensure WIFI address is the same on both computer and watch, scroll down and select Allow. It will bring you back to the previous screen.

Step 6. Now go to Samsung Watch Face Studio on PC load the file *.WFS then select “Run on Device” Click + next to (scan devices) Add your ip address from your watch (example 192.168.1.106) Then add port number that is after your ip: (example 34669) Then click + on the watch to (Pair new device) Add Pairing code from watch to pairing code empty slot in watch face studio. Then Add Pairing Port Number from ip address at the bottom after Example (192.168.1.106:36749) then enter (36749)

Then select ok in watch face studio, and then click on the Your Watch in Devices and the File will be sent to your watch and the face will appear on your watch in about 16 to 20 seconds. If your waiting more than 2 minutes. Most likely something went wrong with the installation. Close Watch Face Studio and try Again. Persistence will get the Job done, Don't give up!!

## About Me
I'm just a Type 1 diabetic that is trying to find solutions for myself and finding Amazing Software's that allow me to see my Offline Blood Glucose Readings, and Treat myself on the fly with little thought. Seeing on my watch face my Blood glucose and Trend, Delta, Timestamp and IOB are an absolute must on my watch face for me. I see the overwhelming need for support on Social Media So I'm sharing my results. But Keep in mind this is all experimental and you use at your own risk, Come Check out My You tube Channel for Basic Installation Videos. 


**Diabetic Masked Man Channel Here:** https://www.youtube.com/channel/UCF-M5IItLP5aJpMiBQtmQKw


## God Bless

