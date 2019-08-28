# CVE2019-2017_POC
Definitely suprising easy to exploit this. Essentially it is based on the improper handling of the tiles_enabled_flag and the inability of the poorly written code to verify invalid value on tile. The difficulty arises on building a payload to succesfully take over the execution flow and achieve RCE.

The delivery methods that are applicable for this exploit seem relatively few since any online service or messaging app will not use libhvec or change the video format so no youtube or whatsapp. Exploitation through browser or email service is defenetly achivable since format will remain the same if you send over email or serve it on your own webserver. 

The current exploit should only work on Android versions 7-9 and requires interaction by the user to click the video. Then you can essentially control the phone with a properly crafted payload.

# Tested on

Huawei Honor 8 (Works)

Samsung s7 (Works)

LG G3 (Android Version 6.0 does not work)

**IF THE MEDIA PLAYER CRASHES IT WORKED!!**


**NOTE:** The payload has been removed from the exploit since there are too many vulrenable phones at this time
