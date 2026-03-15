# Custom Xcode Simulator Device Types

This repository contains **custom device type profiles** for the Xcode
Simulator.\
They allow you to add additional or experimental devices to the
simulator device list.

## Included Device Types

-   Apple Watch IDFK what i'm doing 3
-   iPhone 20
-   MacBook Air 13-inch (M3)
-   iPod touch (8th generation)

Each device is provided as a `.simdevicetype.zip` file.

------------------------------------------------------------------------

# Installation

1.  Download the `.simdevicetype.zip` file you want.
2.  Extract the zip file.
3.  Move the extracted `.simdevicetype` file to:

```{=html}
<!-- -->
```
    /Library/Developer/CoreSimulator/Profiles/DeviceTypes

4.  Restart **Xcode** (if open) and the **Simulator** app.

The device should now appear in the **Simulator device list**.

------------------------------------------------------------------------

# Example (Terminal)

If you prefer using Terminal:

``` bash
unzip "iPhone 20.simdevicetype.zip"
sudo mv "iPhone 20.simdevicetype" /Library/Developer/CoreSimulator/Profiles/DeviceTypes/
```

Restart Simulator afterwards.

------------------------------------------------------------------------

# Notes

-   Administrator privileges may be required to write to `/Library`.
-   These are **custom / experimental device profiles** and may not
    perfectly match real hardware.
-   If the device does not appear, restart Xcode/Simulator or reboot your Mac.
- You will need to manually click the New Simulator Button. 

------------------------------------------------------------------------

# Disclaimer

These device types are unofficial and are not provided or supported by Apple.
