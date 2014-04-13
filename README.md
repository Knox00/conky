Note that any instances of "jake" need to be changed to your username, and things such as /Storage (/media/mydata) need to be changed to your drive directories. 

If you are using a desktop, the "POWER" section can be removed, it it full of battery stats.

If you have more than 2 CPU cores, there must be some edits to the "PROCESSORS" part, for examplle, changing the script from 2 to 4 cores would be made like this:

ORIGINAL

  ${font Arial:bold:size=10}${color Tan1}PROCESSORS ${color DarkSlateGray}${hr 2}
  $font${color DimGray}CPU1  ${cpu cpu1}% ${cpubar cpu1}
  CPU2  ${cpu cpu2}% ${cpubar cpu2}

EDITED

  ${font Arial:bold:size=10}${color Tan1}PROCESSORS ${color DarkSlateGray}${hr 2}
  $font${color DimGray}CPU1  ${cpu cpu1}% ${cpubar cpu1}
  CPU2  ${cpu cpu2}% ${cpubar cpu2}
  CPU3  ${cpu cpu3}% ${cpubar cpu3}
  CPU4  ${cpu cpu4}% ${cpubar cpu4}
  
The FoughtKnight Victory font will need to be installed from this link, unless you want to change it (ctrl-f foughtknight-victory): http://www.dafont.com/foughtknight-victory.font

The Ubuntu font will need to be installed if you aren't running Ubuntu, and aren't planning on changing to another font: http://font.ubuntu.com/

"Ubuntu 14.04 Trusty Tahr" will be needed to be changed to your OS or whatever string you want to display there.

If you are using the internet via ethernet, all instances of "wlan0" must be changed to "eth0"

That's all, folks!
