# Dell Vostro 5490 - EFI - Sonoma

This is an EFI for DELL Vostro 5490 i7-10510U
<br>
Currently built for macOS Sonoma on OpenCore 0.9.9

## EFI Details
**Latest working macOS**: 14.4.1
<br>
**Current OpenCore**: 0.9.9
<br>
**GenSMBIOS**: MacBookPro15,2

## Working
- WiFi
- Bluetooth
- Audio
- Keyboard
- Trackpad
- Display Backlight Fix (No problems at the moment)

## Not Working
- HDMI
- Card Reader (Probably)
 
## How to use
  1. Create directory `EFI` in your pendrive
  2. Clone this repo and paste directiories "BOOT" and "OC" onto created directory
  3. Download [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) to generate unique SMBIOS information. 
  4. Run it and select **Install/Update MacSerial**
  5. Choose **Select config.plist** and paste your config.plist path
  6. Select **Generate SMBIOS** and use **MacBookPro15,2**. Your changes will be merged to your config.plist automatically.
  7. Boot it!


## Credits
https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-10THGEN-COMET-LAKE-PUBLIC
