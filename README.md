# Macbook-Pro-2013-Early-problems

There is an
== Error in Supported OSX ==
in the Wikipedia page...
for the MacbookPro10,1 2013
https://en.wikipedia.org/wiki/MacBook_Pro_(Intel-based)#Software_and_operating_systems

Mackbook Pro 2013 Early 15" with dual graphic card, 
Intel HD3000 and Nvidia GeForce GT 650M 1GB GDDR5. 
Automatically switches between graphics hardware when running macOS.
and that is a big problem.

Late 2013 has 750M

Most MBP 2013 from that era are Damaged, 
Nvidia chip becomes desoldered or damaged, 
a known issue since 2011

http://dosdude1.com/resources.html

that caused Apple to terminate Nvidia partnership in following years, 
and only support AMD GPUs.

Apple offered a very small window of warranty, mostly with-in USA to affected owners.
but most people living outside USA had problems to claim the warranty with authorized Apple resellers.

3rd party / unofficial repair services do re-balling "re-solder" the 650Mm,
but results dont last because the damaged chip,
usually needs a new 650M chip for a proper reballing, and results may vary.

The 2nd problem: 
OSX Catalina requires 650M exclusive, does Not support Intel HD3000,
same happens with OSX HighSierra,
Latest UEFI Firmware 262.0.0
forces MBP 2013 Early to use the damaged 650M by default.
Downloading older Firmare from apple website does Not allow to Downgrade.

https://support.apple.com/en-us/HT201518

https://support.apple.com/kb/DL1848?locale=en_US

https://discussions.apple.com/thread/8144103

https://support.apple.com/kb/DL1450?locale=en_US


OSX Catalina can be installed but has No display, Black Screen.
Because the 650M is Damaged in most MBP 2013 Early models.

with a Damaged 650M the only Option is OSX EL Capitan 10.11.3
if user installs 10.11.6 starts to Fail.
because relies more in the 650M.

MBP Early 2013 15" 
does Not work with OSX Catalina, 
does Not work with OSX High Sierra.

Maybe MBP 2013 with single graphics,
maybe Mid 2013,
probably Late 2013,
but Early 2013 does Not, unless it has a perfectly working 650M.

with a Damaged 650M
the only way to activate intel GPU, in older OSX that does Not require the 650M,
is connecting an HDMI cable to a TV turned-on, wait for OSX to load "usually keyboard backlight turns-on", 
close the lid,
open the lid,
unplug the HDMI cable,
and sometimes also requires to press [Shift] key, 
to Wake-Up / Activate the Retina Backlight and the intel integrated graphics.

MBP 2013 Early with a Damaged 650M only Option is OSX EL Capitan 10.11.3
and installing gfx or gswitch to force integrated graphics.
latest Firmware does Not allow to force GPU / stop automatic switch in Power Options.
