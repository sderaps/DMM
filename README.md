# DMM Watchface

A simple watch face with 5 oversized, extra large complications for better viewing experience for Dexcom G7, xdrip+ companion for the Galaxy watch 7, using glucodata handler app on phone and watch.

Created with Samsung watch face studio.

![](DMM.jpg)

# Install instructions

The **DMM.wfs** file needs to be installed via adb in Watch Face Studio App for Windows or Apple Computer.

Turn ON ADB debugging on the watch, allow connecting via "Wireless debugging" and use the same wifi network on computer and watch.

Load the file in Watch Face studio, then click "Run on Device". That triggers an Call for Developer Options to be unlocked.

When asked to provide the IP Address and Port, Pair New Device with wifi pairing code and new Port Again..

Once the connected, it will recognize the watch, select it and it will send the file direct to your watch face...

Keep in mind Google makes Wear OS 5 more complicated, by creating a "connected device" ADB Timeout.. Meaning after a minute or so you loose connection to ADB and have to start over again with connection process.
