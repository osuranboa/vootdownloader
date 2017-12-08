# Video Stream Downloader For Hotstar,Voot and Dailymotion,AltBalaji  #

### Description ###

* Commandline video downloader for Windows
* Available Chrome Extension and command line downloader for premium Hotstar Videos(not for all) 
* Version 2.0.0
* Added new CLI downloader for AltBalaji Videos

### Step to install the chrome extension ###

* Download the project as zip file and extract it.
* Go to chrome_extension\Extension CRX.
* Open chrome and type chrome://extensions and press enter.
* Drag and drop the vootdownloader.crx file to chrome(just drag and drop to the window it will install automatically).
* Add the extension

### Step to install the Unpacked source file as chrome extension ###

* Download the project as zip file and extract it.
* Open chrome and type chrome://extensions
* Click "Load Unpacked Extension" button.
* Then Browse to the "{extracted folder after you download}\ALL_DOWNLOADS\chrome_extension\src\vootdownloader" folder and select it.     

### Step to download video in chrome extension ###
* First open www.voot.com and open a video that you want to download.
* click the extension and it will show you the current video.
* Click download icon. 
* Video will be downloaded on default Download location of chrome browser.


### Step for download video using Commandline Interface ###
* Open git bash
* Clone the project as zip and extract it.
* Go to vootdownloader directory and type command [sh cli_downloader.sh]
* Now go to browser and hit www.voot.com and play one video and copy the playing video url
* Now again go to git bash and paste the url and press enter
* Video will be downloaded under vootdownloader directory

### Execute AltBalaji CLI downloader from CLI
* After clonning this project please go inside libs/ffmpeg/ folder.
* Open git bash
* write command sh atbalaji.sh and press enter.
* Go to alt balaji webside select a episode . Url should be in https://<domain>/episode/<id> format.
* Copy that and paste in command line and press enter. download will start.
* Video will be available in libs\ffmpeg\altbalaji_videos\ folder

### Limitation ###
* It will only run on windows
* It may be Uninstalled automatically as we do not publish the CRX file in Chrome.


