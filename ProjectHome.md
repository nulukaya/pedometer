<font color='#177F21'>Check out my new Facebook app: <a href='http://apps.facebook.com/movieswapper'><strong><font color='#177F21'>Movie Swapper</font></strong></a> - exchange movies with your friends</font>


# Pedometer - Android app #

_Pedometer_ is an application for [Android](http://www.android.com/about/) phones, that counts your steps.

| **Source code now on [GitHub](http://github.com/bagilevi/android-pedometer)** |
|:------------------------------------------------------------------------------|


## Features ##

Counts your steps, displays your pace, approx. distance, speed and calories burned.

It has an option to notify you by voice in given intervals about any value. You can set a desired pace/speed and get notified when you have to go faster or slower.

## Limitations & tips ##

If not accurate, try adjusting the sensitivity setting. Works best when attached firmly to your body.

On some phones it can't count the steps when the screen is off, try tweaking the "Operational level" setting if this happens.

Not suitable for all day use, as it consumes power constantly.

Drop me an email if you have any problems, suggestions, ideas. You can also create your own version as this is open source software. Have fun!

## Latest changes ##

New in v1.4 (2010-12-25):
  * Using built-in TTS
  * Fix binding to the service
  * Layout extends to the screen, supports various screen sizes
  * Adjust default sensitivity, add more options
  * Fix division by 0 bug

New in v1.3 (2010-04-25):
  * option for keeping screen always on
  * fixed TTS auto installation
  * fixed multiple activity starts

New in v1.2 (2010-04-25):
  * fixed to work on new phones (tested on HTC Desire)

New in v1.1 (2009-06-14):
  * calculate distance and speed based on user's step length
  * calculate approx. calories burned based on step length & body weight
  * repeated voice notifications about any displayed value
  * pause and resume the service
  * reset all values

## Screenshots ##

![http://www.levente.bagi.name/pedometer/p11_main.png](http://www.levente.bagi.name/pedometer/p11_main.png)
![http://www.levente.bagi.name/pedometer/p11_menu.png](http://www.levente.bagi.name/pedometer/p11_menu.png)
![http://www.levente.bagi.name/pedometer/p11_settings.png](http://www.levente.bagi.name/pedometer/p11_settings.png)
![http://www.levente.bagi.name/pedometer/p11_steplength.png](http://www.levente.bagi.name/pedometer/p11_steplength.png)
![http://www.levente.bagi.name/pedometer/p11_setting2.png](http://www.levente.bagi.name/pedometer/p11_setting2.png)
![http://www.levente.bagi.name/pedometer/p11_whattotell.png](http://www.levente.bagi.name/pedometer/p11_whattotell.png)
![http://www.levente.bagi.name/pedometer/p11_main2.png](http://www.levente.bagi.name/pedometer/p11_main2.png)

## Installation ##

  * using the _Market_ application on your phone or
  * by downloading the [Pedometer.apk](http://pedometer.googlecode.com/files/Pedometer-1.4.1.apk) file and issuing `adb install Pedometer.apk`

## Planned Features ##

  * [see issues...](http://code.google.com/p/pedometer/issues/list)

## Statistics ##

| **Date** | **Rating** | **Installs** | **Active Installs** | **Comments** |
|:---------|:-----------|:-------------|:--------------------|:-------------|
| 2009-06-14 | 3.48 (24) | 4335 | 2661 (61%) |  |
| 2009-06-19 | 3.69 (36) | 6159 | 3977 (64%) |  |
| 2009-07-04 | 3.59 (51) | 8568 | 5283 (61%) |  |
| 2009-09-12 | 3.39 (102) | 20776 | 11777 (56%) |  |
| 2009-12-08 | 3.5 (168) | 36983 | 18598 (50%) |  |
| 2010-04-25 | 2.93 (281) | 62813 | 27075 (43%) | 103 |
| 2010-12-25 | 2.77 (567) | 131624 | 41175 (31%) | 207 |

## Additional Information ##

Developed by [Levente Bagi](http://www.levente.bagi.name/)

License: [GNU General Public License, version 3](http://www.gnu.org/licenses/gpl.html)

If you want to create your own version, fork [the project on GitHub](http://github.com/bagilevi/android-pedometer). You must publish the source code under [GPLv3](http://www.gnu.org/licenses/gpl.html) or compatible and wherever you submit your app, state that the source code is available with a link to it. Also, use a different or altered application icon, so that it will be distinguishable from this app.