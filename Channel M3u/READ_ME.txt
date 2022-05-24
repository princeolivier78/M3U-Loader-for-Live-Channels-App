HOW TO :

********************************************************************************************************************************************************************************************
1)TV_LOGOS EXAMPLE:

CHANGE THE URL BELOW

https://www.dropbox.com/s/6389yjjxyajedw3/demo3.png?dl=0

TO THIS :

https://dl.dropboxusercontent.com/s/6389yjjxyajedw3/demo3.png?dl=0

click changed url to get the direct image .
to add the logo inside the playlist just get 6389yjjxyajedw3/demo3.png , look at the tvg-logo="6389yjjxyajedw3/demo3.png"in the format below .

#EXTM3U url-tvg="https://dl.dropboxusercontent.com/s/fyboiekemv5b2bi/M3U_loader.xml?dl=0"
#EXTINF:-1 tvg-id="channel0" tvg-name="Bbc One" tvg-logo="demo0.png" group-title="english",##Dummy Leave me here##
https://etlive-mediapackage-fastly.cbsaavideo.com/dvr/manifest.m3u8
#EXTINF:-1 tvg-id="TRTWorld.tr" tvg-name="Trt" tvg-logo="6389yjjxyajedw3/demo3.png" group-title="english",DEMO 1
https://etlive-mediapackage-fastly.cbsaavideo.com/dvr/manifest.m3u8

Then ADD Logo URL in M3U LOADER LOGO URL like this :

https://dl.dropboxusercontent.com/s/

IF YOU DON'T WANT THE LOGO IN YOUR TV LISTING ,LEAVE THE tvg-logo = EMPTY INSIDE

********************************************************************************************************************************************************************************************

2)CHANGE THE M3U PLAYLIST URL BELOW

https://www.dropbox.com/s/4t0fizavd8ebjco/M3U%20Loader.m3u8?dl=0

TO THIS :

https://dl.dropboxusercontent.com/s/4t0fizavd8ebjco/M3U%20Loader.m3u8?dl=0

to get the direct download of the M3U playlist .


Then ENTER URL in M3U LOADER M3U URL like this :

https://dl.dropboxusercontent.com/s/4t0fizavd8ebjco/M3U%20Loader.m3u8?dl=0

********************************************************************************************************************************************************************************************

3)CHANGE THE XMLTV TV GUIDE URL BELOW

https://www.dropbox.com/s/fyboiekemv5b2bi/M3U_loader.xml?dl=0


TO THIS :

https://dl.dropboxusercontent.com/s/fyboiekemv5b2bi/M3U_loader.xml?dl=0

to get the direct download of the XMLTV GUIDE .


Then ENTER URL in M3U LOADER XMLTV URL like this :

https://dl.dropboxusercontent.com/s/fyboiekemv5b2bi/M3U_loader.xml?dl=0

THATS IT YOU ALL SET,in this example I used Dropbox as example you can use other cloud storage like github or google drive as long as you know how to pull the direct link to the file. 

****REMEMBER NO SPACES INSIDE THE TV IDS,TV LOGOS IDS IN THE TVGUIDE OR THE APP WILL MISSBEHAVE****


