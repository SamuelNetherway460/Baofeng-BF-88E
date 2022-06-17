<h1 align="center">Baofeng BF-88E</h1>
<h3 align="center">Configuration images, manuals, general documentation and .csv format frequency configurations.</h3>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-BF-88E">
  <img src="https://img.shields.io/github/v/release/SamuelNetherway460/Baofeng-BF-88E">
  <img src="https://img.shields.io/github/release-date/SamuelNetherway460/Baofeng-BF-88E">
  <img src="https://img.shields.io/github/issues/SamuelNetherway460/Baofeng-BF-88E">
  <img src="https://img.shields.io/github/downloads/SamuelNetherway460/Baofeng-BF-88E/total">
</p>

## Description
Repository for the Baofeng BF-88E digital radio. Contains all documents relating to the radio i.e., specs, manuals, etc. There is only 1 configuration consisting of the PMR446 (licence free) channels.

## Configuration Status
| Configuration | Last Commit | Latest Release | Release Date |
| :---: | :---: | :---: | :---: |
| PMR446        | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Baofeng-BF-88E/Config-PMR446) | ![version](https://img.shields.io/badge/release-PMR446--vX.X.X-blue) | ![release-date](https://img.shields.io/badge/release%20date-XX--XX--XXXX-red) |

## Radio Specs
- Frequency Range: UHF 400-470MHz
- RF Rated Power: 0.5W/2W
- Channel Capacity: 16
- Channel Spacing: 25KHz
- Operated Voltage: 3.7 V
- Battery: 1500MAh Li-ion
- Battery Life: About 8 hours
- Frequency Stability: ±2.5ppm
- Operated Temperature: -30°c-+60°c
- Antenna Impedance: 50Ω
- Dimensions (L×W×H) (with battery,without antenna): 110×50×32 mm
- Weight (with battery/antenna): 198g
- Communication Range: about 2-4km

## Transmitter
- RF Power Output: 3W
- Modulation: F3E
- Spurious Emission: ≤65dB
- FM Noise: ≤-45dB(W) ≤-40dB (N)
- Audio Distortion: ≤5%
- Transmitting Current: ≤1.3A

## Receiver
- Sensitivity (12dB SINAD): ≤0.20 uVSelectivity: 55dB/50dB
- Intermodulation: ≥65dB
- Adjacent Channel Selectivity: ≥60dB
- Spurious Response: ≥60dB
- Audio Power Output: 1000mW

## Chirp Radio Programming Guide
1. Download and install [Chirp](https://chirp.danplanet.com/projects/chirp/wiki/Home).
2. Download the source / radio images from the [Releases](https://github.com/SamuelNetherway460/Baofeng-BF-88E/releases) page.
3. Launch Chirp.  
![Chirp Launched](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Chirp%20Launched.png)
4. Connect the Baofeng BF-88E to the PC using the USB programming cable.
5. Turn on the radio.
6. In the menu bar, click "Radio" and then "Download From Radio".  
![Download From Radio](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Download%20From%20Radio.png)
7. Select the correct Port, Vendor and Model using the drop down boxes.
8. Click "Ok".
9. Click "Ok".  
![Baofeng UV-5R Instructions](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Baofeng%20UV-5R%20Instructions.png)
10. Wait for Chrip to finish cloning the current radio programming.  
![Cloning Programming](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Cloning%20Programming.png)  
    The current programming will then be displayed.  
![Current Programming](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Current%20Programming.png)
11. In the menu bar, click "File", then "Save As".  
![Save Backup](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Save%20Backup.png)
12. Navigate the File Explorer and click "Save" to save a backup of the current radio configuration.  
![Save Radio Image](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Save%20Radio%20Image.png)
13. In the menu bar, click "File", then "Open".  
![Open Radio Image File Menu Bar](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Open%20Radio%20Image%20File%20Menu%20Bar.png)
14. Navigate the File Explorer and select the Radio .img file.  
![Navigate to Radio Image File](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Navigate%20to%20Radio%20Image%20File.png)
15. Click "Open".  
![Open Radio Image File](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Open%20Radio%20Image%20File.png)  
The radio image file should now be loaded.  
![Radio Image File Loaded](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Radio%20Image%20File%20Loaded.png)
16. Custom configurations such as welcome messages should now be made.
17. Once ready to upload to radio, in the menu bar click "Radio", then "Upload To Radio".  
![Upload to Radio](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Upload%20to%20Radio.png)
18. Select the correct Port and click "Ok".  
![Select Port](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Select%20Port.png)
19. Click "Ok" when the instructions are displayed.  
![Baofeng UV-5R Upload Instructions](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Baofeng%20UV-5R%20Upload%20Instructions.png)
21. The radio image file will now be applied to the radio.  
![Uploading to Radio](https://github.com/SamuelNetherway460/Baofeng-BF-88E/blob/Documentation/res/Uploading%20to%20Radio.png)
23. Once the radio light has finished flashing, and the progress bar is complete / progress window has disappeared, the radio can be switched off and disconnected.
24. Radio programming is now complete and the radio is ready to be used.
