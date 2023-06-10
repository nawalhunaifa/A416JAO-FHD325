# A416JAO-FHD325
EFI file for Asus A416JAO-FHD325

![Screenshot](/screenshotventura.png)

Laptop spec :
- [x] <b>Model</b>: Asus A416JAO-FHD325
- [x] <b>CPU</b>: Intel i3-1005G1 (10rd Gen)
- [x] <b>iGPU</b>: Intel UHD Graphics G7 @ 1GB
- [x] <b>RAM</b>: 8GB DDR4 PC25600 / 3200Mhz
- [x] <b>Storage</b>: 256GB M.2 NVMe PCIe 3.0 SSD
- [x] <b>Audio</b>: Intel Smart Sound Technology
- [x] <b>Wifi</b>: Intel(R) Wireless-AC 9461 
- [x] <b>Trackpad</b>: I2C Interface
- [x] <b> Monitor</b>: FHD (1980x1080) 60hz
- [x] <b>BOOT Loader</b>: OpenCore 0.8.8
- [x] <b>BOOT Mode</b>: UEFI
- [x] <b>BIOS Version</b>: 5.14

<details>
<summary><strong> What's Worked </strong></summary>
<br>

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| QE/CI Enabled Graphics               | ✅ | Config Inject + WhateverGreen.kext |
| Brightness Adjustments               | ✅   | BrightnessAdjust.kext + WhateverGreen.kext |
| CPU Power Management               | ✅   | CPUFriend.kext Costum |
| Audio (C-Media(R))     | ✅  | UTBMap.kext + USBToolBox.kext |
| Trackpad ASUEI2C    | ✅   | VoodoI2C.kext + VoodoI2CHID.kext |
| FN Keys                 | ✅   | DSDT Patch |
| Keyboard backlight      | ✅ | AsusSMC.kext + DSDT Patch |
| Battery Indicator                    | ✅   | ECEnabler.kext + Lilu.kext |
| USB 3.0 and Type-C         | ✅   | SSDT Patch |
| Sleep,Restart and Shutdown                      | ✅   | DSDT Patch |

</details>

<details>
<summary><strong> Not Working </strong></summary>
<br>

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| Builtin WebCam              | ❌   | Feature = Bugs |
| HDMI out                | ❌   | Icelake lmao |


</details>


