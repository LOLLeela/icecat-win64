# icecat-win64

This a fork of gdriggs/icecat-win64 attempt at building a Windows binary of GNU IceCat.
Please see https://www.gnu.org/software/gnuzilla for more information.

I began with instructions from Mozilla for setting up a build environment:
https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Windows_Prerequisites
Make sure you use VS2015 to compile, and be ready to fix the moz.configure to work with the new build enviroment.

I am using gdriggs's .mozconfig, I downloaded the latest source from a GNU mirror, ran "mach configure", "mach build", then "mach build installer". The result is the installer checked in here. 
This build is only for 64-bit versions of Windows.