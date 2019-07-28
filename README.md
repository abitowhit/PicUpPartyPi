# PicUpPartyPi
Python Scripts for PicUpPartyPi
https://247coding.com/drupal/?q=picup

PicUpPartyPi consists of a few small scripts to automatically take pictures at an event.
Concise information, images and testing can be found at on 247Coding.com using the link above.

The premise is to load onto a pi zero connected to a usb charger.  Initial tests provide about
10 hours of runtime with 50% still remaining on battery.

Set the PartyPi in an optimal location before the party begins.
Use your mobile device to start/stop automatic pictures or force a picture once the party starts.
As it is taking pictures in the background, the PartyPi will display pre-loaded images on the local 3x5 screen or
HDMI connected display/TV.

There are only a few scripts.  Flask is used to display images to the local chromium browser
in kiosk mode on boot.  Javascript cycles through the images to display.
Flask html page allows you to remotely control the party pi using your cell phone or for
other party members to view the image display on their mobile device.
There are only a few html pages.  Minimally the first one for the local display and the second for control
of the PartyPi.

As images are taken at your predetermined interval, they are uploaded to a website via FTP.
A third php page uploaded to this website will display all of the pictures within the FTP directory.

The 3D printed case is designed to also house a pi NOIR camera mounted on the top of the unit, so make
sure it is not blocked from view of the room.  To avoid "butt shots", place the unit where people cannot
directly stand in front of it (unless that is what you are going for).



abitowhit
