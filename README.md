# CVE2019-2017_POC
Defenetly suprising easily to exploit this. it essentially based on the improper handling of the tiles_enabled_flag and the inability to verify invalid value on tiles, the difficulty arises on building a payload to succesfully take over the execution flow and achieve RCE.

The delivery methos for this exploit seem relatively few since any online service or messaging app will not use libhvec or change the video format. Exploitation through browser or email service is defenetly achivable since format will remain the same. 

The current exploit should only work on Android versions 7-9.

# Tested on

Huawei Honor 8 (Works)

Samsung s7 (Works)

LG G3 (Android Version 6.0 does not work)

**IF THE MEDIA PLAYER CRASHES IT WORKED!!**


**NOTE:** The payload has been removed from the exploit since there are too many vulrenable phones at this time
