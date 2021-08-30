# Alpha 87A Node Red Flow
Node Red flow to control an Alpha 87A amplifier.

Flow is currently configured to use a USB-Serial cable directly connected to a Raspberry PI. It's best to configure the PI to always assign the same USB "device" to ensure the flow is able to connect to the amp. This flow is using the name ttyUSB_Alpha87A. Configuration using udev is beyond the scope of this doc.       


