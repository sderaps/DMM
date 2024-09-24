# Welcome to Diabetic Masked Man!

## Diabetic Oversized Watch Faces For MDI Injection Created with Samsung Watch Face Studio that are Compatible with Wear OS 5+ , and OS 4 using GlucodataHandler for the Visually Impaired.

**Please Note:  
Faces are being periodically updated. You will be able to tell if the (.wfs) has been worked on by looking at the upload date.**

Wear OS 5 Compatible Watches:
Pixel Watch 3 , Galaxy Watch 7 




## Wear OS 5+ Watch Faces for Dexcom G7, Xdrip+, using GlucodataHandler Complications

[DMM1_DexcomG7_Xdrip.wfs](https://github.com/sderaps/DMM/blob/a99a45b547c678e245dffda8d8a1cd8d0372e177/DMM1_DexcomG7_Xdrip.wfs)

![DMM1](https://raw.githubusercontent.com/sderaps/DMM/main/DMM1%20Galaxy%20Watch%20%207%2044mm.jpg)

[DMM2_DexcomG7_Xdrip.wfs](https://github.com/sderaps/DMM/blob/a99a45b547c678e245dffda8d8a1cd8d0372e177/DMM2_DexcomG7_Xdrip.wfs)

![DMM2](https://raw.githubusercontent.com/sderaps/DMM/main/DMM2_Dexcom_G7_Xdrip.jpg)

[\[DMM4_Dexcom G7_Xdrip.wfs\]](https://github.com/sderaps/DMM/blob/main/Dmm4_DexcomG7_Xdrip.wfs)

![DMM4](https://raw.githubusercontent.com/sderaps/DMM/main/DMM4_DexcomG7_Xdrip.jpg)

## Wear OS 5+ Watch Faces for Other CGMs, using GlucodataHandler Complications


[DMM3_Universal.wfs](https://github.com/sderaps/DMM/blob/ebc463ef4a033574e918236807612a5fc479a4ea/DMM3_Universal.wfs)

![DMM3](https://raw.githubusercontent.com/sderaps/DMM/main/DMM3%20Universal.jpg)

## Wear OS 4 Watch Faces

I'm creating Similar Watch Faces with using WatchFaceStudio_1.6.1.0, which are  compatible with Wear OS 4. You can find those watch faces in File Folder Here: [Wear OS 4 Watch Faces](https://github.com/sderaps/DMM/tree/main/Wear%20OS%204%20Compatible%20Watch%20faces)

## Program Needed for Watch Face Installation

**Download Samsung Watch Face Studio**

WatchFaceStudio_1.7.9.exe or Higher ONLY For Wear OS 5): https://developer.samsung.com/watch-face-studio/download.html

**Download Samsung Watch Face Studio for Wear OS 4**

WatchFaceStudio_1.6.10.exe for Wear OS 4 only. Watch faces found Here: "[Wear OS 4 Compatible Watch Faces](https://github.com/sderaps/DMM/tree/main/Wear%20OS%204%20Compatible%20Watch%20faces)



## Warning!

These watch face complications uses very specific glucodatahandler customization. Other customizations will "NOT" look right and the font will be tiny or oversized.  You have my permission to download, alter and use the *.wfs file to fit your personal needs. 

*These Watch Faces Were created specifically because of Googles Wear OS Changes on Wear OS 5, making Watch Face Apps Currently Like Pujie Watch Faces no longer Compatible. 

**Older Versions of Wear OS Watches, Will not work with watch faces posted on the Main Page. You must go to folder HERE "[Wear OS 4 Compatible Watch Faces](https://github.com/sderaps/DMM/tree/main/Wear%20OS%204%20Compatible%20Watch%20faces)". I know they work and have been tested with Galaxy Watch 6 44mm. Keep in mind you must use WatchFaceStudio_1.6.10.exe to "Run on Device" Install.  

** For older versions of Wear OS Watches, You also might be able to find a good watch face setups and a simple tutorial on my Youtube channel: Diabetic Masked Man , Link is at the Bottom in the "About Me" section of the Page.  

## Summary
Oversized watch faces for MDI Injections with Extra Large Complications for the visually impaired.  Works with Dexcom G7, Xdrip+, Libre 3 and other CGMs supported by GlucoDataHandler Android App for the current (Galaxy watch 7 or Pixel Watch 3). The  Complications used are very specific to the watch face using  GlucodataHandler app on phone and watch. Installing the watch face on Wear OS 5 is a bit complicated, and you have to use WatchFaceStudio_1.7.9.exe or Higher program. You Load the *.wfs file and send it to watch via ADB using the Function "Run on Watch" in the Watch Face Studio PC Application. Detailed install instructions below.

**GlucodataHandler Android App** 
Google Play Go Here:
https://play.google.com/store/apps/details?id=de.michelinside.glucodatahandler&hl=en_US

**Xdrip+ Android App ** 
Stable Build Here
https://xdrip.readthedocs.io/en/latest/install/download/
Nightly Build Here:
https://github.com/NightscoutFoundation/xDrip/releases


## Watch Face Specific Customizations

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

**DMM3** Universal Watch Face for Libre 3, Dexcom G7 using GlucodataHandler specific Customizations

1. Glucose and Trend (big and Colored)
2. Delta Big
3. Glucose Time stamp
4. Samsung or Google Timer
5. Samsung Heart Rate Monitor
6. Watch Battery Level

**DMM4** Watch Face From the top left Complication going across using Glucodatahandler specific Customizations are as follows.

1. Glucose time stamp
2. Glucose and Trend (big and colored),
3. IOB
4. Samsung or Google Timer
5. Delta big
6. Watch Battery Level


## Installation

Samsung Watch Face Studio Gave me allot of problems connecting to my watches during the install "Run On Device", I had to spend quite allot of time trying to install the watch face over and over again. Here are the Steps:

Step 1. Connect your watch and computer to the same Wi-Fi network

Step 2. On your Watch Go to Settings/Connections and Turn off Bluetooth.

Step 3. Enable Developer Options on Watch go to Settings > About device > Software info, then tap the Build number until “Developer options enabled” appears on the screen. Swipe the screen "left to right" to Go back and select Developer Options at the bottom of /settings

Step 4. Put your watch on a usb charger and open Developer Options select “Stay awake when charging” select “ADB Debugging” select “wireless debugging then check wireless debugging in enabled,
 
  on the next screen, Now ensure WIFI address is the same on both computer and watch, scroll down and select Allow. It will bring you back to the previous screen.

Step 5. Now go to Samsung Watch Face Studio on PC load the file *.WFS then select “Run on Device” Click + next to (scan devices) Add your ip address from your watch (example 192.168.1.106) Then add port number that is after your ip: (example 34669) Then click + on the watch to (Pair new device) Add Pairing code from watch to pairing code empty slot in watch face studio. Then Add Pairing Port Number from ip address at the bottom after Example (192.168.1.106:36749) then enter (36749)

Then select ok in watch face studio, and then click on the Your Watch in Devices and the File will be sent to your watch and the face will appear on your watch in about 16 to 20 seconds. If your waiting more than 2 minutes. Most likely something went wrong with the installation. Close Watch Face Studio and try Again. Persistence will get the Job done, Don't give up!!

This watch background are basic because I cannot create an .apk installation file. So If you want to edit the Watch face background in Watch Face Studio, I've uploaded a few you can choose from, Just put the .png files in your hard drive watch back ground directory in watch studio and add them. 

## Troubleshooting Watch Face Installation! 

1. "Run of Device" Does nothing and Runs forever! 
Note:  If "Run on Device" is trying to send the watchface to watch and does nothing for over 2 minutes. Do This! 

2. Close out Watch Face Studio and Reboot PC

3. Go to Watch and "Revoke debugging Authorizations in Developer Settings

4. Turn Off Wireless Debugging

5. Turn Off ADB Debugging

6. Turn Off Smart Watch and boot again.

7. On Watch Make sure Bluetooth is Off

8. Turn "ON" WIFI and Make Sure Wifi is the Same Address on both Watch and PC. 

9. Open Watch Face Studio on PC, and load the watch face

10. Click "Run on Watch" then select the "+"

11. Now go back to watch, and turn on ADB Debugging, Click on Check Mark to Allow. 

12. Go to Wireless Debugging, Toggel it ON, Then Click "allow" for Network.

13. Scroll Down and follow procedure Described In (Step 6 Installation Instructions.

This Should Work, If Not, Keep Doing this same procedure over and over until it works.  
  
Remember, after Successful Installation. Disable, ADB and Wireless Debugging, Disable Wifi and Enable Bluetooth. Also make sure "Stay Awake While Charging" is turned OFF in Developer Setting. 

As you can see, from the above I had allot of problems installing these watch faces. But with persistence it worked. I'm sorry I don't know how to make this easier. I spend endless hours trying to solve, The Troubleshooting Above seemed to fix the issue. On Samsung Developer Site, you will be able to see I'm not the only one with this issue and they really offered no Help. 
Here: https://forum.developer.samsung.com/t/run-on-device-problem/20008/55


## About Me
I'm just a Type 1 diabetic that is trying to find solutions for myself and finding Amazing Software's that allow me to see my Offline Blood Glucose Readings, and Treat myself on the fly with little thought. Seeing on my watch face my Blood glucose and Trend, Delta, Timestamp and IOB are an absolute must on my watch face for me. I see the overwhelming need for support on Social Media So I'm sharing my results. But Keep in mind this is all experimental and you use at your own risk, Come Check out My You tube Channel for Basic Installation Videos. 


**Diabetic Masked Man Channel Here:** https://www.youtube.com/channel/UCF-M5IItLP5aJpMiBQtmQKw


## God Bless

