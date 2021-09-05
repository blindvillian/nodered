# Alpha 87A Node Red Flow - de N0VD
Node Red flows to control an Alpha 87A amplifier.

-- alpha_87a_minimal is the initial v0.9.0 BETA release and will require that the AlphaMax softward be installed.  This is a minimal interface and assumes automatic operation of the amp.

-- alpha_87a_full is a full featured NR flow that allows for 87As with or without the AlphaMax software to be remotely controlled.

Flow is currently configured to use a USB-Serial cable directly connected to a Raspberry PI. It's best to configure the PI to always assign the same USB "device" to ensure the flow is able to connect to the amp. This flow is using the name ttyUSB_Alpha87A. Configuration using udev is beyond the scope of this doc, however, these links should get your going. 
  https://unix.stackexchange.com/questions/66901/how-to-bind-usb-device-under-a-static-name
  https://askubuntu.com/questions/978485/udev-rule-with-serial-for-ttyusb-not-working

Revision History
******************************************************************
Version: v0.9.1 BETA
Initial Release:: 30 August 2021 (v0.9.0)
Author: Kelly Jones - N0VD
Current Version: https://github.com/blindvillian/nodered
Description: Flow to remotely control an Alpha 87A amp

Flow is currently configured to use a USB-Serial cable directly 
connected to a Raspberry PI. It's best to configure the PI to 
always assign the same USB "device" to ensure the flow is able 
to connect to the amp. This flow is using the name ttyUSB_Alpha87A. 
Configuration using udev is beyond the scope of this doc.

v0.9.1 : 4 Sept 2021
  Greatly expanded features and functionality so flow will work with
  87As without the AlphaMax software. Also updated the UI to be more 
  appealing than the out of the box theme.

v0.9.2 : 5 Sept 2021
  Fix the band-segment to band-button mappings so the button 
  "lights up" for all segments in a band.

******************************************************************

Enjoy!
Kelly - N0VD       


