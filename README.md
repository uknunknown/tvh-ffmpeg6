# tvh-ffmpeg6

Updated on 30 apr. 2023

This project is intended to help you patch tvheadend master in order to compile with ffmpeg 6.0

Clone tvheadend:

**git clone https://github.com/tvheadend/tvheadend.git**

Patch files:

**patch -p0 < ffmpeg6.patch**

compile like you regularly compile;
I personally use:
 
 **cd tvheadend**
 
 **./Autobuild.sh**