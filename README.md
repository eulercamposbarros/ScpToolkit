# ScpToolkit
[Nefarius ScpToolkit](https://github.com/nefarius/ScpToolkit) is a Windows Driver and XInput Wrapper for Sony DualShock 3/4 Controllers. I just add support for fake gamepads over bluetooth.

## Credits
### Community
Big thanks to [Nefarius](https://github.com/nefarius/ScpToolkit) for publising this great work!

## Installation How-To
1. Connect your Dongle (only needed if you want to use it wirelessly) and controllers (yes, *all* of them) via USB and let Windows install its default drivers. **Leave them plugged in during the entire installation process!**
2. Download the [latest release of the ScpToolkit Setup and FakePadSupport dll's](https://github.com/eulercamposbarros/ScpToolkit-FakePadBluetoothSupport/releases/latest) to an arbitrary location on your PC.
3. Run the Setup and follow it's instructions. Should be fairly straight-forward.
4. Wait for the Setup to finish.
  * If you're performing a fresh installation, run the Driver Installer afterwards.
  * If you're upgrading from an older installation you may skip the Driver Installer.
5. When running the Driver Installer, choose your Bluetooth and controller devices you like to use with ScpToolkit.
6. The next step depends on your operating system:
 - Vista: check the Force Install option.
 - Win 7/8/8.1/10: leave it unchecked (or check if you're facing installation troubles, might help).
7. Click Install.
8. Copy the contents of **ScpToolkit_FakePadSupport.zip** to the folder where you installed the ScpToolkit (Something like *C:\Program Files\Nefarius Software Solutions\ScpToolkit*). You may create a backup of the originals files instead of replacing then. (ScpControl.dll and ScpControl.Shared.dll)
9. You're done!

![Install Screenshot](http://nefarius.at/wp-content/uploads/2013/12/31-10-_2015_13-27-55.png "Install Screenshot")

