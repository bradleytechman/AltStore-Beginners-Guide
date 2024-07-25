# AltStore

 Since a lot of people have been asking how to use AltStore, sideload, or IPA files for apps such as YouTube; This guide will tell you how to use AltStore, sideloading, issues, and how to solve them. 

# Apples restrictions

The difference between AltServer and AltStore is that AltServer is what you use to install AltStore and refresh your apps so they don’t expire. You have to refresh apps every 7 days or else they expire. You can also have a max of 10 app IDs. 1 app (including AltStore) takes up 1 to 2 or sometimes 3 app IDs.

# Using AltServer on Mac
So first off, you will want to get AltServer from [AltStore.io](https://altstore.io). 

So after you’ve clicked MacOS, a file called AltServer.dmg should’ve been downloaded. Once you open it, you will see AltServer downloaded to downloads or wherever you downloaded it. When you open it, an icon should appear in the corner. (note that if you have Bartender or a menu bar client it may be hidden) when you click it, it should show a lot of options. Hover over the one that says “Install AltStore". Once hovered over, select your device and type your Apple ID to install it. This is safe, none of your data is recorded by AltStore. Once you hit install, it should work. If it doesn’t, make sure your device is connected over cable. Once installed, You now have AltStore! 

# Using AltServer on Windows


Using AltServer on Windows is relatively the same process as on Mac. Go to [AltStore.io](https://altstore.io) and download it for Windows. You should get a file called altinstaller.zip Run setup.exe Not AltInstaller, Altinstaller is to remove or repair AltServer. ( would be better if Riley named it something else!) then click next, install, and say yes. You getting closer! Next get iTunes ( [32-bit devices](https://secure-appldnld.apple.com/itunes12/001-80042-20210422-E8A351F2-A3B2-11EB-9A8F-CF1B67FC6302/iTunesSetup.exe) [64-bit devices](https://secure-appldnld.apple.com/itunes12/001-80053-20210422-E8A3B28C-A3B2-11EB-BE07-CE1B67FC6302/iTunes64Setup.exe) ) and iCloud, [64 and 32-bit](https://updates.cdn-apple.com/2020/windows/001-39935-20200911-1A70AA56-F448-11EA-8CC0-99D41950005E/iCloudSetup.exe). Please do not get it from the Microsoft store or it will not work. You also don’t have to sign into iTunes or iCloud with your Apple ID. Ok, got iCloud and iTunes installed? Click the AltServer icon in the tray, install Altstore, on your phone, and type in your Apple ID. If you don’t feel comfortable, you can use a dummy Apple ID, but this doesn’t get sent to Altstore or Riley. Just apply for authentication. They are not saved as well. Once you hit install, it should work. If you have any issues, scroll down to issues under how to use AltServer on Linux. See if your issue is there before commenting, please! You might also want to turn notifications on for AltServer.

Video:

# Using AltServer on Linux

AltLinux is a GUI for AltServer Linux, both being made unofficially. To install it, follow the instructions at the link below.

https://github.com/i-love-altlinux/AltLinux#install-altlinux

# Do Not Use 3uTools to install iPA files

Do not use 3Utools. It has been proven to be modifying jailbreak developers’ jailbreaks without permission which is piracy, sending data to China about your phone, and Using a pirated and modified version on Appsync Unified (A jailbreak tweak that they did not get permission to modify). Do not use it.

# Issues & Fixes

# How do I turn on developer mode?
<details>
<summary>How do I turn on developer mode?</summary>
<br>
Developer mode can be turned on by going to Settings > privacy and security > scroll to the very bottom and enable developer mode > restart > open AltStore > click ok if it says you need developer mode > turn on. This is ok and your security is fine.
</details>

# How do I trust AltStore?

To trust AltStore, go to Settings < General < VPN & Device Management < (the email that you used to install AltStore ) < trust 

# My device isn’t showing up.

Thanks to u/BWC_4_Wife for this info

On Windows C:\ProgramData\Apple\Lockdown (start, type in %ProgramData%\Apple\Lockdown ) or

on a Mac: Go to /var/db/lockdown in Terminal You can remove everything in this folder, which will remove trust from every device. Refresh your apps faster 

# My apps aren't refreshing wirelessly

!WINDOWS ONLY! u/wolo_prime had a lot of trouble getting Altstore apps (uYou+) to refresh my apps wirelessly. He installed every version of iTunes, reinstalled services, windows updates, wifi, and firewall settings.

What finally worked was restarting the Apple Mobile Device Service. To do it on Windows, you open the command in admin mode. Wnd key, type "cmd", and right-click "run as administrator".

When it's opened you type:

net stop "Apple Mobile Device Service"

wait a couple of seconds

net start "Apple Mobile Device Service"

Your device should appear on iTunes a few seconds afterward. You also find the process running in task manager and right-click "restart" which would do the same.

Credit to u/cancerism for this idea!

# Another way to automate your refreshes if Background refresh doesn't work

Background refresh is supposed to automate refreshing but it never worked for u/cancerism.

I'll assume that you've already set up wifi sync and auto start altserver with your computer

Just use shortcut automation and pick a time that you're most likely to be at home. Turn off Ask Before Running which will be on by default

# YouTube++/uYou+ isn’t working, what can I do?

First off, don’t use a random YouTube++, use uYou+ it’s much better than a random file you found off of a shady site.

# If I use the same apple ID on both my iPad and iPhone, will it affect the number of sideloading apps?

It shouldn't, in my testing, you can use the same apple ID 

How vulnerable is my iPhone if I enable developer mode?

Not that vulnerable. Still safe even after it’s turned on. Apple might just be trying to scare you

# I’m getting error 1100

Make sure you are signed into iTunes

Be sure to authorize iTunes → Accounts → Authorizations → Authorize This Computer

Enable iTunes Wi-Fi sync for your phone

Minimize iTunes when done. Make sure it is still open in the background

Run altserver as admin

Hope this helps!

Written by u/chux-e.

# I’m stuck on the login screen, what do I do?

Written by u/archiep0gi

Ensure the following:

    ⁠Your device and your AltServer Device (PC/Mac/Laptop) is connected on the same WiFi or connected via cable.

    ⁠If connected to the same WiFi, temporarily disable your firewall or anti-virus (this worked for u/archiep0gi).
    
# I'm not receiving notifications from apps I sideloaded

You can only get notifications from apps you sideload by paying $99 a year to apple for a developer account. Idk how altstore can send notifications though. 

# Is there any way to bypass/extend the expiration from 7 days?

With an apple developer account for $99 a year, you get, 365 until it expires, then you refresh, unlimited app id's, your P12 signing certificate, notifications, access to the developer betas, and the rest is here 
You can get IPA files from here. now stop asking plz

# The icon isn't showing up in the tray, what do I do?
Credit to RyzenGaming#5928 for figuring this out. u/wukkyy got the idea but RyzenGaming made a guide that went into more detail and said more steps you needed to do.

Step 1- Download the vivetool from here 👉🏻(https://github.com/thebookisclosed/ViVe/releases)

Step 2- Create a folder name vivetool without any spaces in the name, in C Drive.

Step 3- Now Extract all the files from the zip to That vivetool folder you had created in Step 2.

Step 4- Open Up the CMD (Run as Administrator).

Step 5- Copy Paste & Run this Command in CMD 👉🏻 c:\vivetool\vivetool.exe /disable /id:26008830

Step 6- After Running the Command it will Show you a Message saying 👉🏻Successfully Set Feature Configuration ) which means the command is successfully implemented.

Step 7- Now the only thing you need to do afterwards is that restart your PC.

Step 8- After Restarting your PC, Launch the** AltServer as Administrator**, Guess what, !!!Boom!!!🎆 u can see the AltServer Icon in your taskbar tray bar.

# There is no provisioning profile with the requested identifetr on this team.(3017)

!YOU MUST USE ALTSERVER FOR THIS UPDATE!

Reinstall AltStore from AltServer, then you should be on the newest version. Please note that you do not need to delete AltStore.

# Where is the install mail-plugin option? 

Since AltServer 1.7, the mail-plugin is no longer needed.

# AltServer cannot find my device (windows only)
 Thank you to [syphant](https://github.com/syphant) for this find!

 For Windows users experiencing issues with wireless refreshing that are resolved by restarting Apple Mobile Device Service, you can create a batch file (open notepad, paste it in, and save as something.bat) that contains the below:

`@echo off`
`net stop "Apple Mobile Device Service"`
`timeout /t 30`
`net start "Apple Mobile Device Service"`

You can then create a scheduled task that runs this batch file with elevated privileges (necessary for restarting services) once per day or at whatever interval you wish, this should prevent the issue entirely, as this problem seems to happen when the service has been running for a long period of time for whatever reason.




# Have the AltStore beta? Here are sources you can add! 

Clicking on the link will open in AltStore You can get the beta by paying monthly for [Riley and Shane’s Patreon](https://www.patreon.com/rileyshane). 

[https://raw.githubusercontent.com/vizunchik/AltStoreRus/master/apps.json](https://tinyurl.com/mtatsd3a)

[https://quarksources.github.io/quantumsource++.json](https://tinyurl.com/5add3ubk)

[https://repo.starfiles.co/public](https://repo.starfiles.co/public)

[https://web.archive.org/web/20210225095501if_/https://appybois.com/](https://tinyurl.com/2vjt6p7f)

[https://quarksources.github.io/quantumsource.json](https://tinyurl.com/y6d8un9t)

[https://randomblock1.com/altstore/apps.json](https://tinyurl.com/3vjxvuzb)

[https://alts.lao.sb](https://tinyurl.com/mr5ymvkm)

[https://floridaman7588.me/altjb/altsource.json](https://tinyurl.com/4rwjsfan)

[https://ipa.cypwn.xyz/cypwn.json](https://tinyurl.com/5cujbntv)

[https://hann8n.github.io/JackCracks/MovieboxPro.json](https://tinyurl.com/yc2ppkce)

[https://flyinghead.github.io/flycast-builds/altstore.json](https://tinyurl.com/5svryy7z)

[https://www.appfair.net/fairapps-ios.json](https://tinyurl.com/5hautux4)

[https://appmarket.tech/altstore.json](https://tinyurl.com/msuss6pm)

[https://repo.starfiles.co/dae0adfa29](https://tinyurl.com/2rw9yrp5)

[https://repo.starfiles.com/6b1b6f1120](https://tinyurl.com/47mx5k8u)

[https://raw.githubusercontent.com/qnblackcat/AltStore/gh-pages/apps.json](tinyurl.com/2x9cvfbv)

[https://bit.ly/wuxuslibrary](https://tinyurl.com/bdeskrjz)

[https://bit.ly/wuxuslibraryplus](https://tinyurl.com/mr3swam8)

(If you copy the links and see they are link shorteners and get suspicious, this is only because GitHub does not support URL Schemes)

# Compiling
Coming Soon!

# URL Schemes

URL Schemes can be used in 2 different ways. Adding a source to the AltStore beta or installing an app from a link. 
You can use a URL scheme by typing either `altstore://source?url=[the URL of the source` or `altstore://install?url=[download url]` . 
# Credits

u/xXEnjo1PandaXx(Shane) - Moderator that stuck the post

u/wukkyy - Found Windows 11 tray bug fix

u/chux-e - Fix for error 1100

u/archiep0gi - Fix for being stuck on the login screen

u/cancerism - Another way to automate your refreshes

u/BWC_4_Wife - Fix for device not showing up

(ex main dev)maxasix - AltLinux GUI

Nick Chan#0001 - AltLinux GUI

nebula#5513 - AltLinux GUI

yourfriend#5919 - AltLinux GUI

xerz#9055 - AltLinux GUI

RyzenGaming#5928 - Better explation for Windows 11 Tray Bug fix

The end. Thank you for taking your time to read this because this took literal AGES so please, consider pressing the upvote and star button. Thank you to Shane for sticking this post, you made my day!

if there are words in unnecessary places it’s because I used Grammarly to touch everything up

EDITS: ALOT of grammar, added beta sources and removed a few, formatting, added issues, added URL schemes tab, compiling tab, and removed a broken source
