Find My Device (FMD) Server allows you to track and control your Android device remotely.

It is the server component for the [FindMyDevice](https://gitlab.com/Nulide/findmydevice/) Android app (available on [F-Droid](https://f-droid.org/packages/de.nulide.findmydevice/)).

### Features

- **Locate your device**: View your device's location on a map.
- **Remote control**: Send commands to your device from the web interface.
  - Ring the device.
  - Lock the device.
  - Take pictures with the front/back camera to see surroundings.
  - Wipe/Reset the device (factory reset).
- **View data**: Access photos taken by the device and location history.

### Integration with YunoHost

- This package installs the Django-based FMD Server.
- You need to install the FindMyDevice app on your Android device and configure it to point to your server URL.
