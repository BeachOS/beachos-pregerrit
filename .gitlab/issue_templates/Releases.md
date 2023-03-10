|  |  |
| ------ | ------ |
| Android Version |  |
| Security patch |  |
| BeachOS version |  | 
| Build number | ** ** | 
| Previous Build Number |  |
| OTA Test Build number |  | 
| OTA Test2 Build number |  | 

Notes:

Devices:
* [ ] taimen | Pixel 2 XL
* [ ] walleye | Pixel 2
* [ ] crosshatch | Pixel 3 XL
* [ ] blueline | Pixel 3
* [ ] bonito | Pixel 3a XL
* [ ] sargo | Pixel 3a
* [ ] coral | Pixel 4 XL
* [ ] flame | Pixel 4
* [ ] sunfish | Pixel 4a
* [ ] jasmine_sprout | Mi A2

Checklist:
* [ ] Tag release
* [ ] Build from tag
* [ ] Sign release
* [ ] Make sure device is running "Previous build" and that the bootloader is locked.
* [ ] Install OTA, **-testing** - incremental should mean quick download
* [ ] Run through SetupWizard, check with microG enabled/disabled and select all/some/no F-Droid apps on different devices
* [ ] Testing restoring a backup from USB
* [ ] Verify the build information in Settings -> About. It should match the details up top.
* [ ] Verify any new features / bugfixes, refer to the changelog for details.
* [ ] Wi-Fi (network strength when close to router, speedtest)
* [ ] Mobile Data ()
* [ ] Bluetooth (On, Pairing, audio)
* [ ] Calls (Normal, VoLTE)
* [ ] Text Messages / SMS
* [ ] eSIM
* [ ] Location (GPSTest, Maps)
* [ ] Camera (Still images, video, front and back)
* [ ] Flashlight / torch
* [ ] Sensors
* [ ] Hotspot
* [ ] Fingerprint scanner
* [ ] Face unlock
* [ ] Device sounds
* [ ] BeachVPN
* [ ] F-Droid
* [ ] Verify microG configuration if enabled (microG Settings -> Self Check)
* [ ] Final step, test OTA updates from this build to a newer build, **-otatest** - this will be a full OTA, big download
* [ ] Verify that the build number matches the test build number above. (Via `adb shell getprop`)
* [ ] Optionaly, test the completely new test build, **-otatest2** - this will be a full OTA, big download
* [ ] Verify that the build number matches the test build number above. (Via Settings)
* [ ] Move to **-beta**
* [ ] Move to **-stable**

/label ~Releases
