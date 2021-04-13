[Go Back](index.html)

# The Better Windows
___
This was written on 7/12/2020(That is d/m/y for my American frens)

So you have to use Windows ,either because of hardware compadibilites with Linux, Work or just wanting to play games.

But you dont want any of the mobile apps and less of the privacy issues.
OR you do not want any frequent updates breaking your computer

**DO NOTE:** may have issues running software with this method.

What you need my friend is Windows 10 LTSC and a lot of patience.

Windows 10 LTSC is a special version of windows that is meant for enterprise. 
Since entrerprise requires stable systems this version of windows does not update as often. As of 2020 Windows 10 LTSC is based on 1809. A clean ISO (which I do not provide) is required for this guide.

if you want to find how to get a clean ISO look at /fwt/

The other thing you need is an existing windows installation(VM is also fine). And also a program called [Optimize-Offline](https://github.com/DrEmpiricism/Optimize-Offline)

To use Optimize-Offline you need to go to the releases page, Get the source code and then run the file Start-Optimize.ps1 using powershell.

The rest is fairly straightforward, you remove applications and features that you will *not* use on Windows such as the mobile apps and then choose a compression level.
Compression can take a while and you may want to choose None since you may want to test the iso for breakages.


# Software

***

Well windows is nothing without software so here are some recommendations

| Software Type | Software |
|---|---|
|Browser|Firefox, Firefox ESR, Chromium(woolys)|
|E-Mail|Thunderbird|
|Games|GoG, Steam|
|Image Viewer|nomacs,qView|
|Painting/Picture editing|Krita, Gimp,if you find a copy of CS6 that is also good|
|Video Player|mpv, VLC|
|Package Manager|scoop.sh is the only real package manager for windows|