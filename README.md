# icecat-win64

This is a fork of gdriggs/icecat-win64 attempt at building a Windows binary of GNU IceCat.
Please see https://www.gnu.org/software/gnuzilla for more information.

I started with the instructions from Mozilla for setting up a build environment:
https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Windows_Prerequisites
Make sure you use VS2015 to compile, and be ready to fix the moz.configure to work with the new mozilla build enviroment. Slight changes are made to the that screw it up.

I am using gdriggs's .mozconfig, I downloaded the latest source from a GNU mirror, ran "mach configure", "mach build", then "mach build installer". The result is the installer checked in here. 
This build is only for 64-bit versions of Windows.

If all you are after is the compiled copies. I use this as my primary browser across Windows and Linux, I will be updating this when I compile a new version. However I am doing it by hand so it may not always be quick.
Submit an issue if I forget.

If you run into any problems running it try installing Visual C++ Redistributable for Visual Studio 2015, https://www.microsoft.com/en-us/download/details.aspx?id=48145

Ideally in the future I would like this to use a GNU compiler, but I just wanted to get this working for now as I was unable to locate a recent IceCat binary for Windows x64.