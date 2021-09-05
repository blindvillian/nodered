# Alpha 87A Node Red Flow - de N0VD
Node Red flows to control an Alpha 87A amplifier.

-- alpha_87a_minimal is the initial v0.9.0 BETA release and will require that the AlphaMax softward be installed.  This is a minimal interface and assumes automatic operation of the amp.

-- alpha_87a_full is a full featured NR flow that allows for 87As with or without the AlphaMax software to be remotely controlled.

Flow is currently configured to use a USB-Serial cable directly connected to a Raspberry PI. It's best to configure the PI to always assign the same USB "device" to ensure the flow is able to connect to the amp. This flow is using the name ttyUSB_Alpha87A. Configuration using udev is beyond the scope of this doc, however, this link should get your going.  https://unix.stackexchange.com/questions/66901/how-to-bind-usb-device-under-a-static-name

Enjoy!
Kelly - N0VD       


