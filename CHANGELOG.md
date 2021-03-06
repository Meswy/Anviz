## UNRELEASED
BREAKING CHANGES:

FEATURES:

BUG FIXES:

IMPROVEMENTS:

SECURITY:

MISC:

UPGRADE NOTES:

## v2.0.9
UPGRADE NOTES:
* GetDeviceID is now deprecated in favor of DeviceID property


## v2.0.0
BREAKING CHANGES:

* `AnvizManager` doesn't need DeviceID anymore since it's requested to the connected device automatically
* `TcpParameters` class now implements `IPAddress` for IP fields and `PhysicalAddress` for MAC

FEATURES:

* Set device network info
* Set device SN (only on supported Anviz devices)
* Set device ID
* Reboot device
* Reset device to Factory Settings
* Unlock door
* Get/set basic settings
* Get/set advanced settings
* Set/delete staff data
* Set fingerprint template
* Enroll fingerprint interactively
* Set/get facepass template
* Upload/delete records
* Server mode support
