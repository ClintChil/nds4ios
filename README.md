nds4ios - iOS 5 ~ 7
=======
### This is not finished software.

### Please do not open issues complaining about games being slow or crashing on devices with only 256MB of RAM (like the iPod touch 4); we know about it.

### IMPORTANT: WHEN OPENING ISSUES, PLEASE STATE YOUR DEVICE, iOS VERSION, AND WHETHER YOU ARE JAILBROKEN OR NOT. PLEASE ALSO TELL US WHERE YOU DOWNLOADED THE APP FROM.

### PLEASE DO NOT DISTRIBUTE THIS BY CODE-SIGNING IT, UPLOADING, THEN TELLING OTHERS TO DOWNLOAD IT FROM YOU. WE PROVIDE AN OFFICIAL WAY TO DISTRIBUTE ALREADY. THIS IS A FAIR WARNING.

nds4ios is a port of nds4droid to iOS, which is based on DeSmuME.

http://nds4ios.infinidev.org/

[DeSmuME](http://desmume.org/) 

[nds4droid](http://jeffq.com/blog/nds4droid/)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MCAFUKL3CM8QQ)

We all work hard to make this into software that users will enjoy and love. If you enjoy this software, please consider making a donation to help us create and provide better things.

Install Instructions
------------------------

### Option 1: Download it from Karen's Pineapple (KarenP/Flame)

If you're jailbroken, please follow the instructions here: http://nds4ios.angelxwind.org/i/?page/downloads#jailbroken

If you're NOT jailbroken, please follow the instructions here: http://nds4ios.angelxwind.org/i/?page/downloads#notjailbroken

### IMPORTANT: THE NON-JAILBROKEN VERSION OF THE APP IS EXTREMELY OUTDATED, AND WILL NOT, AND CANNOT BE UPDATED ANY TIME SOON. 

### Option 2: Compile it yourself

IMPORTANT: Make sure your working directory is devoid of spaces. Otherwise, bad things will happen.

1.  Open a Terminal instance and go to your working directory.

2.  Do
<code>git clone https://github.com/InfiniDev/nds4ios.git</code>

3.  then
Navigate to the "nds4ios" folder in your working directory.

4. Open "nds4ios.xcodeproj", connect your device, select it on Xcode and click the "Run" button (or Command + R). Don't build it for the iOS Simulator. IMPORTANT: Make sure you change your running scheme to Release first. Otherwise you will get errors on compile!

#### Option 2a
1. Alternatively, run
    <code>xcodebuild -configuration Release</code>
   from Terminal and then copy the resulting *.app bundle to your /Applications directory on your device.


How To Load ROMs
------------------------
##### Since this apparently needs explaining

### Option 1 - Via Safari
1. In nds4ios, tap on the button in the upper right hand corner.
2. Download a ROM package of a ROM that you own the actual game cartridge for from a site such as CoolROM. It may come in a zip file. You do not have to have any sort of download manager for this, Safari will download zip files.
3. Tap the "Open in..." button in the top left hand corner, and select nds4ios.
4. nds4ios will automatically unzip the file, delete the readme, find the .nds file, and refresh itself. Your ROM should show up in the list. Magic!

### Option 2 - Via iTunes File Sharing / iFunBox / iExplorer
## NOTE: THIS METHOD ONLY WORKS ON THE NON-JAILBROKEN VERSION.
1. Plug your device into your computer and launch iTunes.
2. Go to your iDevice's info page, then the apps tab.
3. drag and drop .nds files that you have (preferably ones you legally own the actual game cartridge for) into the iTunes file sharing box for nds4ios.
4. Kill nds4ios from the app switcher if it's backgrounded, and launch it again to see changes.

### Option 3 - Via Safari/Chrome Download Enabler
1. If you're jailbroken, grab one of the many download tweaks available for Mobile Safari or Chrome for iOS, or grab one of the many web browsers available with download managers built in, such as [Cobium](https://itunes.apple.com/us/app/cobium-simple-browsing/id502426780?mt=8) (This is totally not a shameless plug).
2. With the new browser or tweak, download a rom, preferably one you own the actual cartridge for.
3. Using iFile or similar too, move the .nds file to the nds4ios directory, into the documents folder.
4. Kill nds4ios from the app switcher if it's backgrounded, and launch it again to see changes.

### Option 4 - Via AFC2 / OpenSSH / iFunBox / iExplorer
1. **You must be jailbroken in order to do this.**
2. Install OpenSSH if you plan to utilise SCP (SSH) to transfer ROMs.
3. If you do not wish to utilise SCP, then download iFunBox/iExplorer/similar tool that uses AFC2 over USB and install it on your computer.
4. Drag your ROMs into the directory: /User/Documents/
5. Saves go in: /User/Documents/Battery/

To-do
------------------------
###### We'll get to these, really!
* JIT/Dynarec (very hard to achieve this using the llvm clang compiler, in progress)
* OpenGL ES rendering
* Fix loading game saves on some games
* Ability to set the folder the rom chooser reads from
* Minimise memory footprint
* Add more localizations (currently have: English, Traditional Chinese, Simplified Chinese, Spanish, French, Japanese)
* Much more.

Contributors
------------------------
###### We stand on the shoulders of these people.
* [The DeSmuME developers](http://desmume.org/)
* [Jeffrey Quesnelle (jeffq), the developer of nds4droid](http://jeffq.com/blog/nds4droid/)
* [rock88](http://rock88dev.blogspot.com/)
* [Karen Tsai (angelXwind)](http://angelxwind.net/)
* [Brian Tung (inb4ohnoes)](http://brian.weareflame.co/)
* [Jesús A. Álvarez (maczydeco)](http://twitter.com/maczydeco)
* [W.MS](http://github.com/w-ms/)
* [Riley Testut (rileytestut)](https://github.com/rileytestut)
* [David Chavez (dchavezlive)](http://dchavez.net)
* [Michael Zhang (Malvix_)](https://twitter.com/Malvix_)
* [Angela Tsai (vanillastar67)](https://twitter.com/vanillastar67)
* [WinOCM (winocm)](https://twitter.com/winocm)
